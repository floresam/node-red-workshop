# Lab 3: Get to know your Pi
1.	Insert a Sense HAT input node. The Sense HAT node is under the Raspberry Pi category and has 1 output port (right side) and no input ports (left side).
2.	Insert a debug node.
3.	Wire the output port of the Sense HAT node to the input port of the debug node.
4.	Deploy your flow
5.	Using the debug pane, look at the events that come from the Sense HAT. Disable the debug node by clicking on it to stop the flow of data. Expand a debug message to see the contents.
6.	Insert a Sense HAT output node. The Sense HAT output node can be found under the Raspberry Pi category and has 1 input port (left side) and no output ports (right side).
7.	Insert an inject node
8.	Set the inject node’s payload to the string “*,*,red”
9.	Wire the inject node’s output port to the Sense HAT output nodes input port.
10.	Deploy your flow.
11.	Trigger the inject node by clicking on it.
