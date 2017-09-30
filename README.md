How to compile:
1. Must have libssl-dev installed:
sudo apt-get install libssl-dev

2.compile:
g++ -Wall -std=c++11 -pthread pastrydht.cpp -o pastrydht -lcrypto

