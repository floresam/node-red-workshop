# Lab 3: Get to know your Pi
1.	Insert a Sense HAT input node. The Sense HAT node is under the Raspberry Pi category and has 1 output port (right side) and no input ports (left side).   
![SenseHAT node](./images/pi-node-palette.png)
2.	Insert a debug node.   
![Debug](./images/debug-node-palette.png)
3.	Wire the output port of the Sense HAT node to the input port of the debug node.   
![SenseHAT node wired to debug node](./images/sensehat-wire-debug.png)
4.	Deploy your flow.   
![Deploy button](./images/deploy-button.png)
5.	Using the debug pane, look at the events that come from the Sense HAT. Disable the debug node by clicking on it to stop the flow of data. Expand a debug message to see the contents.   
![Debug node disable](./images/click-debug-node.png)
6.	Insert a Sense HAT output node. The Sense HAT output node can be found under the Raspberry Pi category and has 1 input port (left side) and no output ports (right side).   
![SenseHAT output node](./images/pi-node-palette.png)
7.	Insert an inject node.   
![Inject node](./images/inject-node-palette.png)
8.	Double click on the inject node and set the inject node’s payload to the string “*,*,red” then click the Done button.   
![Inject node config](./images/inject-node-config.png)
9.	Wire the inject node’s output port to the Sense HAT output nodes input port.   
![Inject wired to SenseHAT](./images/red-wire-pi.png)
10.	Deploy your flow.   
![Deploy button](./images/deploy-button.png)
11.	Trigger the inject node by clicking on it.   
![Click inject node](./images/click-inject-node-red.png)
12. Note how your Pi's SenseHAT changes to red!   
![WHOA](http://gph.is/2AmePHo)