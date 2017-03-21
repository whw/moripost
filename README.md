# moripost

  curl https://api.lob.com/v1/letters \
    -u <<<<<<<<< GET FROM LOB CONSOLE >>>>> \
    -d "description=Demo Letter" \
    -d "to[name]=William Williams" \
    -d "to[address_line1]=36 Cervantes Blvd" \
    -d "to[address_line2]=#5" \
    -d "to[address_city]=San Francisco" \
    -d "to[address_state]=CA" \
    -d "to[address_zip]=94123" \
    -d "to[address_country]=US" \
    -d "from[name]=Spike Williams" \
    -d "from[address_line1]=70 Liberty St" \
    -d "from[address_line2]=#6" \
    -d "from[address_city]=San Francisco" \
    -d "from[address_state]=CA" \
    -d "from[address_zip]=94110" \
    -d "from[address_country]=US" \
    --data-urlencode "file=<html><head><meta charset=\"UTF-8\"><link href=\"https://fonts.googleapis.com/css?family=Open+Sans\" rel=\"stylesheet\" type=\"text/css\"><title>Lob.com Sample Letter</title><style> *, *:before, *:after { -webkit-box-sizing: border-box; -moz-box-sizing: border-box; box-sizing: border-box; } body { width: 8.5in; height: 11in; margin: 0; padding: 0; } .page { page-break-after: always; } .page-content { position: relative; width: 8.125in; height: 10.625in; left: 0.1875in; top: 0.1875in; background-color: rgba(0,0,0,0.2); } .text { position: relative; left: 20px; top: 20px; width: 6in; font-family: sans-serif; font-size: 30px; } #return-address-window { position: absolute; left: .625in; top: .5in; width: 3.25in; height: .875in; background-color: rgba(255,0,0,0.5); } #return-address-text { position: absolute; left: .07in; top: .34in; width: 2.05in; height: .44in; background-color: white; font-size: .11in; } #return-logo { position: absolute; left: .07in; top: .02in; width: 2.05in; height: .3in; background-color: white; } #recipient-address-window { position: absolute; left: .625in; top: 1.75in; width: 4in; height: 1in; background-color: rgba(255,0,0,0.5); } #recipient-address-text { position: absolute; left: .07in; top: .05in; width: 2.92in; height: .9in; background-color: white; }</style></head><body> <div class=\"page\"> <div class=\"page-content\"> <div class=\"text\" style=\"top: 3in\"> The grey box is the safe area. Do not put text outside this box. If you are using the data argument, you can add variables like this: {{variable_name}}. </div> </div> <div id=\"return-address-window\"> <div id=\"return-logo\"></div> <div id=\"return-address-text\"></div> </div> <div id=\"recipient-address-window\"> <div id=\"recipient-address-text\"></div> </div> </div> <div class=\"page\"> <div class=\"page-content\"> <div class=\"text\"> This is a second page. </div> </div> </div></body></html>" \
    -d "data[variable_name]=Willie" \
    -d "color=true"
