# Lab 1: Your First Flow
1.	Start Node-RED. Instructions are available in the official Node-RED documentation for [running locally](https://nodered.org/docs/getting-started/running) or [running on a Raspbery Pi](https://nodered.org/docs/hardware/raspberrypi)
2.	Using a web browser, access the Node-RED editor at {IP_ADDRESS}:1880 where {IP_ADDRESS} points to the device running Node-RED.
3.	Insert an inject node. The inject node is under the input category.[Inject Node](./images/inject-node-palette.png)
4.	Insert a debug node. The debug node is under the output category.
5.	Wire the output port of the inject node to the input node of the debug node by dragging the mouse.
6.	Deploy your new flow.
7.	Click on your deployed inject node to send data to the debug node.
8.	Click on the debug tab in the information pane to see what was received by the debug node.
9.	Configure the debug node to show the entire message.
10.	Deploy the updated flow
11.	Click on the inject node to send data.
12.	Look at the whole message object now displayed in the debug pane.
13.	Add a function node in between your inject and debug node. The function node is under the function category.
14. Delete the existing wire between the input node and the debug node. You can delete a wire by left clicking on it then pressing the delete key.
14.	Write the following code in the function node to create a human readable date. This code should be put into line 1 of the function node. ```msg.payload = new Date(msg.payload).toString();```
15.	Deploy your new flow
16.	Click on the inject node to send data.
17.	Look at the message object with a human readable date now displayed in the debug pane.
