# Distributed Hash Table : Pastry Algorithm
Pastry, a scalable, distributed object location and routing substrate for wide-area peer-to-peer applications. Pastry performs application-level routing and object location in a potentially very large overlay network of nodes connected via the Internet. It automatically adapts to the arrival, departure and failure of node.

### How To compile:
1. Must have libssl-dev installed:
```
sudo apt-get install libssl-dev
```

2. Compile:
```
g++ -Wall -std=c++11 -pthread pastrydht.cpp -o pastrydht -lcrypto
```

