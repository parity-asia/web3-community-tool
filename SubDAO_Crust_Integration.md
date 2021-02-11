# SubDAO-Crust Integration

## 1. Crust 
Crust provides a decentralized storage network of Web3.0 ecosystem. It supports multiple storage layer protocols such as IPFS, and exposes storage interfaces to application layer.

## 2. Solutions

### 2.1 SubDAO DApp/website deployment

SubDAO could deploy websites or DApps on the Crust/IPFS network. The process is as follows:
1. SubDAO stores a webpage in IPFS (also supporting the storage of a folder), and obtains corresponding file CID;
2. SubDAO places storage order with these CID in Crust Network;
3. SubDAO deploys the website domain with the CID on IPNS;
4. Users can access the website or DApps deployed on Crust/IPFS;
* For exapmle: [polkadot apps wallet with IPFS](https://polkadot.js.org/) (IPFS Version)

### 2.2 DAO data storage
SubDAO can store files, such as rich text materials or forum discussion data, submitted by users on Crust/IPFS Network. The process is as follows:

1. SubDAO combines rich text documents or forum discussion contents into files or folders and stores them on IPFS to obtain corresponding file CIDs;
2. SubDAO places storage orders for these CIDs on Crust Network;
3. SubDAO users can use these CIDs to retrieve corresponding files on Crust/IPFS Network;

## 3. Development phases

Crust [Storage Order](https://wiki.crust.network/docs/en/crustIntegrationGuide) is expected to be available at the end of February. Consequently, we divide the development of SubDAO into two phases.

### Stage 1：SubDAO-IPFS integration

* Time: Before March 1st 
* Development details: It is recommended that SubDAO integrate the [IPFS standard interfaces](https://docs.ipfs.io/reference/) including ipfs add, ipfs get, ipfs gateway and ipns in this stage 
* Target: SubDAO can deploy Dapps on the local IPFS, and SubDAO's rich text and discussion data can be accessed through the local IPFS network


### Stage 2: SubDAO-Crust integration

* Time: After March 1st
* Development details: SubDAO integrates the storage order features of Crust 
* Target: SubDAO data is reliably stored on Crust/IPFS Network

