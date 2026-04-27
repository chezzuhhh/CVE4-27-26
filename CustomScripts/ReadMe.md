CustomScripts/ contains a few scripts I built and used for various purposes while conducting this research. These scripts came in handy in different stages of discovering this vulnerability (plus going beyond cwe-295, and leveraging it to discover other vulnerabilities), and I hope these tools also come in handy for anyone interested in recreating this PoC.


## mitmToJson.py
Converts .mitm data to json
  #### Info/Flow:
    opens a .mitm file and reads the captured flows (requests/responses)
    extracts the raw state data from each flow
    writes everything to a json file, handling any bytes by converting them to readable strings


## AccessPoint.sh
fillertext
  #### Info/Flow:
    fillertext


## pcapParser.py
Tool for parsing pcaps for specified fields
  #### Info/Flow:
    fillertext
