# Lab 2: Going Online with HTTP
1.	Insert a http input node
2.	Double click on the http input node and set the URL property to welcome
3.	Insert a change node. Change nodes can be found under the function category of the palette.
4.	Wire the http node output port to the change node input port
5.	Set the payload to a custom message of your choice
6.	Insert an http response node. Http response nodes can be found under the output category of the palette.
7.	Wire the change node output port to the http response node input port.
8.	Deploy your updated flow.
9.	Using a web browser, access {YOUR_NODE_IP}:1800/welcome
10.	You should see your custom message displayed in the browser window.
