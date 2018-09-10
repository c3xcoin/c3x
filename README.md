# C3X

<img src="https://i.imgur.com/QVY55XR.png" alt="C3X" width="200"/>


This is new maintained c3xcoin repo
-------------

Install guide:
-------------

run:
* sudo apt-get install build-essential libssl-dev libboost-all-dev libgmp3-dev git libdb5.3++-dev libminiupnpc-dev libtool autotools-dev autoconf
enter:
* cd c3x/src/leveldb
run:
* chmod +x build_detect_platform
make:
* make -f makefile.unix
* strip c3xd


| Conn3x        | C3X           | Coin  |
| ------------- |:-------------:| -----:|
| Algorithm           | X11 (PoW/PoS/MN)  | C3X |
| Total Supply        | 500M    |  C3X  |
| Masternode          | 100000  |  COLLATERAL  |
| Masternode          | 80%  |  from POS reward  |
| Coin maturity: | Confirmation   | 20 blocks   |
| Transaction | Confirmation   |  4 blocks  |
| Transaction Fee | 0.001   |    |
| Block size          |   2   |  MB  |
| Block time          |   4   |  Min  |
| POW          |   200 C3X   |  until block 129600  |
| POW          |   10 C3X   |  from block 129601  |
| POS          |   100%   |  until block 129600  |
| POS          |   50%   |  until block 259200  |
| POS          |   10%   |  from block 259201  |


Configuration file
______________


| conn3x.conf        | 
| ------------- |
| rpcuser=c3xrpc           |
| rpcpassword=x        |
| rpcport=46055          | 
| port=46044         |
| dns=1          |
| server=1          |
| listen=1          |
| daemon=1          |
| dnsseed=1          |
| discover=1          |


Links
-----

Click [here](#) for more info.
