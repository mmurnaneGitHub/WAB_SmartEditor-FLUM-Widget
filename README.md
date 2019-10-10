## WAB_SmartEditor-FLUM-Widget
Customized SmartEditor Widget (Add Comment) for FLUM (https://wspdsmap.cityoftacoma.org/website/FLUM/) and Tideflats Subarea Plan (https://wspdsmap.cityoftacoma.org/website/PDS/Tideflats/).

Version 2.13

INSTRUCTIONS:
1. Copy popup.css to \jimu.js\css\popup.css
2. Copy strings.js to \widgets\SmartEditor\nls\strings.js 
3. Copy Widget.js to \widgets\SmartEditor\Widget.js



Note: Add alias to config file (not an option in WAB):  "label": "Contact Info (Optional)"
* popup.css removes edit ability from map marker popup.
* strings.js changes label to " Allow movement of point"
* Widget.js toggles Summary button off to start editing and removes snapping text from mouse tooltip.

FUTURE RELEASE: Increase comment (and contact) box height and add word-wrap (DIDN'T WORK) (.dijitTextBox - height: 100px; word-wrap: break-word;) in /jimu.js/css/dojo-override.css

