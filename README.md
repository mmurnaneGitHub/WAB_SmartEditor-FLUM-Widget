## WAB_SmartEditor-Widget
Customized SmartEditor Widget (Add Comment) for FLUM and Tideflats Subarea Plan. 
Version 2.12

INSTRUCTIONS:
1. Copy Widget.js to \widgets\SmartEditor\Widget.js
2. Copy strings.js to \widgets\SmartEditor\nls\strings.js 
3. Copy popup.css to \jimu.js\css\popup.css
   
Note: Add alias to config file (not an option in WAB):  "label": "Contact Info (Optional)"
* Widget.js toggles Summary button off to start editing and removes snapping text from mouse tooltip.
* strings.js change editGeometry value to " Allow movement of point"
* popup.css removes edit ability from map marker popup.

FUTURE RELEASE: Increase comment (and contact) box height and add word-wrap (DIDN'T WORK) (.dijitTextBox - height: 100px; word-wrap: break-word;) in /jimu.js/css/dojo-override.css

