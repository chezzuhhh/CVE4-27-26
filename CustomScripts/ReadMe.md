# Custom scripts used for various purposes while conducting this research

## mitmToJson.py
Converts .mitm data to json
  ### Flow:
    opens a .mitm file and reads the captured flows (requests/responses)
    extracts the raw state data from each flow
    writes everything to a json file, handling any bytes by converting them to readable strings
