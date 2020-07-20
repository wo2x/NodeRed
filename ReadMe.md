These flows can be imported into Node Red. I will be periodically updating and adding flows.

In Node Red click on the Menu icon in upper right. Choose Import and then choose select file and select the file to import. Choose new Flow then Import.

Please note - my flows require additional Dashboard nodes to be downloaded to Node Red. These dashboard nodes should be installed before importing any of my flows.

Click on the three horizontal lines in the upper right corner and choose Manage Palette. When that window opens choose Install.

In the search modules window search and install the following

node-red-contrib-msg-resend
node-red-contrib-ui-led
node-red-contrib-ui-level
node-red-dashboard
node-red-node-wol
node-red-contrib-string

After those are installed reboot the Pi then you can import my flows.

On the right side click on the dashboard icon and you will see a bunch of tabs labeled WO2X Shack Control. Expand them by clicking on the v arrow in front of them. You will then see the groups (KPA1500, ROTOR, etc). You can drag all the groups to one tab so they all show up on the dashboard page together. To delete the unused tabs afterwards just click on edit to the right of the tab name and in the window that opens choose Delete.

73 Dave wo2x
