# Nilan graphics for Home Assistant (Lovelace)
Home Assistant: Graphics for Nilan ventilation (use with Lovelace). 

The graphics shows the speed and direction of the air-flow, and the color changes according to states of: Cooling/Heating/Standby. I have the Nilan VPL15, which is only for air-heating/cooling (no water-heating). You might need to adjust the yaml-file if you have other states.

Installation - from Home Assistant folder:
Upload image-files in the www-folder in Home Assistant in a sub-folder called "nilan". Add all additional folders. These contain the actual graphics.
Add the suggested "lovelace.yaml" code in your own "ui-lovelace.yaml" file. 
Prereq:
1. Connection to Nilan through EspHome: https://github.com/Jopand/esphome_components
2. Config-template-card from https://github.com/iantrich/config-template-card
 
Animations are made with MS Powerpoint, then exported from Powerpoint to gif's and refined using Photohshop.
All files made in Powerpoint and Photoshop are included. Feel free to use and make your own customization - and share your findings/suggestions etc. in the Facebook group: https://www.facebook.com/groups/667765647316443
