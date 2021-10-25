# geth-private-blockchain
Simple implementation of a private blockchain network using geth

To start the network, generate a key for the boot node:
```
bootnode -genkey boot.key
```
Then use the generated key to initialize the bootnode:
```
bootnode -nodekey boot.key
```
Make a note of the enode generated. 
![image](https://user-images.githubusercontent.com/33353586/138731164-f0fa73e4-9b66-423a-ba1f-9ee08694aa00.png)

