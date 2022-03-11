# Project 3: BGP Router

### The goal of this project is to manage multiple sockets in a simulated network
### Approach

We began this project by using the sample code provided as the skeleton for our project. We built our code on top of what was provided and followed the instructions in the project description. We started by routing the incoming packets to the relevant functions, including plenty of print statements to test the functionality of the code. 

### Functionality

In brief, our router carries out the following functions:

* Accepts route update messages from the BGP neighbors, and forwards updates as appropriate
* Accepts route revocation messages from the BGP neighbors, and forwards revocations as appropriate
* Forwards data packets towards their correct destination
* Returns error messages in cases where a data packet cannot be delivered

### Challenges Faced

The major challenge we faced was that the router started correctly but crashed midway. We solved it by using print statements and modifying the functions that weren't implemented correctly. Apart from that, there were minor issues in printing the output in the specified format, but we fixed that during debugging.
