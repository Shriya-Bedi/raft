# Project 6: Distributed Key-Value Database

### The goal of this project is to achieve consistent replication in a hostile network.
### Approach

We began this project by using the sample code provided as the skeleton for our project. We built our code on top of what was provided and followed the instructions in the project description. We started by routing the incoming packets to the relevant functions, including plenty of print statements to test the functionality of the code. 

### Functionality

In brief, our sender and receiver carry out the following functions:

* The sender accepts data from STDIN, sending data until EOF is reached
* The sender and receiver work together to transmit the data reliably
* The receiver prints out the received data to STDOUT without errors
* The sender and receiver print out specified debugging messages to STDERR
* Both the sender and receiver gracefully exit
* Our code can transfer a file with any number of packets dropped, damaged, duplicated, and delayed, and under a variety of different available bandwidths and link latencies

### Challenges Faced

The major challenge we faced was retransmitting the message efficiently. We embedded print statements and modified the functions that were implemented incorrectly. Apart from that, there were minor issues but we fixed that during debugging.
