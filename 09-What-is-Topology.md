# What is Topology?

The physical arrangement of the computer system/node, which is connected to each other via communication medium is called topology.

## Types of topology --
- BUS
- RING
- STAR
- MESH
- Hybrid
- Tree

1. **BUS topology** - In bus topology, one long cable acts as a single communication channel & all the devices are connected to this cable.

### Advantages of BUS topology
	1. Easy to add/remove nodes in a network
	2. Required only cable
	3. It is less expensive
	4. It broadcast the message to each device which are connected through the cable.
	5. It is easy to maintain.
	6. In case of any computer failure, there will be no effect of the other devices.

### Disadvantages of Bus topology
	1. If cable failed, entire network failed
	2. Can't send private messages
	3. Takes more time to pass the messages from one place to another place
	4. The length of cable is limited
	5. In this toplogy, data is transmitted in only one direction

2. **RING topology ** - It is called ring topology because it form a ring. In this topology each node is strongly connected with its adjacent node.

### Advantages of RING topology
	1. It has a strong network
	2. Each an every node can share data with another node connected through a ring topology
	3. Transmission rate is high
	4. The data send through RING topology will be broadcasted.

### Disadvantages of RING topology
	1. Difficult to add new node/computer
	2. If we want to send data from a source to destination machine then data will un-necessary passed to all nodes
	3. Single point of failure, that means if a node goes down entire network goes down
	4. It is very diffcult to recover the ring topology if any particular machine is not working properly
	5. We can not send private messages

3. **STAR topology** - In star topology, all the nodes are connected with a central device called HUB, and the sharingof data is only possible through HUB.

### Advantages of STAR topology
	1. It broadcast the messages.
	2. It is less expensive due to less cables
	3. Easy to add new nodes without affecting rest of the network
	4. If one node failed, then it would not be failur of entire network

### Disadvantages of STAR topology
	1. Required a network device like HUB, Switch etc.
	2. If two nodes wants to share data, sharing is only possibe through HUB
	3. Is hub is failed, entire network will be failed.
	4. We can not send private messages

4. **MESH topology** - In this topology, each an every computer is directly connected with each other, so we can directly send the data to the destination machine without going to intermediate machine.

### Advantages of MESH topology
	1. We can send private messages
	2. All nodes are directly associated with another node so, it provides point ot point connection.
	3. Unlike ring topology, if a particular machine is failed then entire network will not be failed.
	4. Multiple devices can send or receive data simultaneously

### Disadvantages of MESH topology
	1. Difficult to add some new node because each an every computer directly connected with another one
	2. If a particular machine not working then, we can not send or receive data from the faiure machine

5. **Hybrid topology** - Combination of various different topology is called hybrid topology.

6. **Tree topology** - In this topology, all the nodes are connected like a branches of tree. The combination is BUS and STAR topology is called the Tree topology.

