# DXP-Coin-Wallets

To run windows DXP-qt. just download DXP-qt.zip file extract it and execute. No any dependencies required.


To run Linux DXP-qt and dxpcoind you need to install dependencies by following commands.

sudo apt-get install build-essential libtool autotools-dev automake pkg-config libssl-dev libevent-dev bsdmainutils git cmake libboost-all-dev

sudo apt-get install software-properties-common

sudo add-apt-repository ppa:bitcoin/bitcoin

sudo apt-get update

sudo apt-get install libdb4.8-dev libdb4.8++-dev

sudo apt-get install libminiupnpc-dev

sudo apt-get install libdb5.3++-dev


After that you start your DXP-qt or dxpcoind on your system.

DXP-qt can run on Ubuntu 16.04 and Ubuntu 18.04 with above dependencies.
For start node use btdcoind and run it on Ubuntu 16.04 LTS.

Please Update Your Config file with addnode attribute to connect daxxplatinum blockchain with below nodes

"134.209.56.85", 
"167.99.43.94",
"159.65.203.202"

