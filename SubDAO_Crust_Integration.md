# SubDAO-Crust Integration

## 1. Crust introduction
Crust provides a decentralized storage network of Web3.0 ecosystem. It supports multiple storage layer protocols such as IPFS, and exposes storage interfaces to application layer.

## 2. Solutions

### 2.1 SubDAO DApp/website deployment

SubDAO could deploy websites or DApps on the Crust/IPFS network. The process is as follows:
1. SubDAO stores a page in IPFS (you can also store a folder directly), and obtains corresponding file CIDs;
2. SubDAO generates places storage orders with these CIDs in Crust Network;
3. SubDAO deploys the website domains and the CIDs on IPNS;
4. Users can access website and DApps deployed on Crust/IPFS;
* For exapmle: [polkadot apps wallet with IPFS](https://polkadot.js.org/) (IPFS Version)

### 2.2 DAO data storage
SubDAO could store files such as rich text materials or forum discussion content submitted by users on the Crust/IPFS network. The process is as follows:

1. SubDAO combines rich text documents or forum discussion contents into files or folders and stores them in IPFS Network and obtains corresponding file CIDs;
2. SubDAO generates places storage orders with these CIDs in Crust Network;
3. SubDAO users could use these CIDs to retrieve corresponding files from Crust/IPFS Network;


## 3. Development plan


The [storage order](https://wiki.crust.network/docs/en/crustIntegrationGuide) function of Crust is expected to go online at the end of February. Therefore, we divide the development of SubDAO into two stages.


### Stage 1：SubDAO integrates IPFS

* Time: Before March 1st 
* Development work: It is recommended that SubDAO to integrate the [IPFS standard interfaces](https://docs.ipfs.io/reference/) in the first stage, including ipfs add, ipfs get, ipfs gateway and ipns
* Target: SubDAO can deploy DApp in the local IPFS, and SubDAO's rich text and discussion data can be accessed through the local IPFS network

### Stage 2: SubDAO integrates Crust

* Time: After March 1st
* Development work: SubDAO integrates the Crust storage order function
* Target: SubDAO data is reliably stored by Crust/IPFS network


