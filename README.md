# Project 6: Distributed Key-Value Database

### The goal of this project is to achieve consistent replication in a hostile network.
### Approach

We began this project by using the sample code provided as the skeleton for our project. We built our code on top of what was provided and followed the instructions in the project description. We started by routing the incoming packets to the relevant functions, including plenty of print statements to test the functionality of the code. 

### Functionality

In brief, our program implements a simplified version of the Raft consensus protocol. The datastore runs multiple times, in parallel, and uses the Raft protocol to maintain consensus among the replicas. We used local UDP sockets to emulate a LAN, with each of the replicas connecting to a single UDP socket
*
### Challlenges Faced

The major we faced was sending enough packets successfully. We had to modify the code and add classes to fix this. We also embedded print statements and modified the functions that were implemented incorrectly.
