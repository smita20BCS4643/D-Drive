# D-Drive
Decentralized Storage Space using Blockchain and IPFS Protocol

## INTRODUCTION 

### Problem Statement 

Cloud-based storage pointed out the problem of data privacy and security, as there is an involvement of a centralized entity or a third party. The proposed system introduced the need for blockchain based decentralized storage to maximize the data privacy and security.


### Proposed Solution

- This proposed D-drive, an IPFS-based decentralized storage space to solve the problem.
Decentralized storage using blockchain and IPFS will allow us to upload file in a decentralized way, allowing us to share in a trust less censorship resistant fashion.
- D-Drive is a software solution trying to prove that centralized cloud-based storage applications Can be decentralized, more secure, and efficient. 
- We proposed developing a web-based application that provides a user interface, from which the user can directly share their data or files.
- Then, the user file is encrypted and stored across a peer-to-peer network using IPFS protocol instead of HTTP protocol and a cryptocurrency will be used as a payment -mechanism. 
- D-Drive’s primary objective is to provide secure decentralized storage space.


## Technologies Used
- Ubuntu 20.04
- Truffle: Framework for creating Ethereum smart contracts.(solidity programming language)

- Ganache: It is the blockchain that will run on our computer to run transactions and deploy smart contracts without having to pay real money.

- Metamask: Browser extension to connect the browser to the blockchain. It is Ethereum wallet to turn our browser to Blockchain browser.

- Web3.js: Collection of libraries that allows you to interact with a local or remote Ethereum node using HTTP, IPC, and WebSocket (connects our application to the blockchain)
 
- ReactJS: JavaScript library used for frontend.

- Solidity: Solidity is an object-oriented programming language for implementing smart contracts

- IPFS: The InterPlanetary File System is a protocol and peer-to-peer network for storing and sharing data in a distributed file system.


## Flowchart
           
<img width="500" alt="Flowchart" src="https://user-images.githubusercontent.com/101444257/174783078-b1df312c-02d4-45c3-ab1e-26de00adc7ae.png">


## A Quick Walkthrough of The Project
-  The proposed developing a web-based application that provides a user interface, from which the user can directly upload or share their data and files over a decentralized network. The proposed solution works in multiple segments.
-  Firstly, the user needs to create an account on metamask and login with their credentials.
-   Then, the user needs to connect their metamask account with
their wallet. The user’s account address and wallet balance are
fetched in the metamask account through web3.js
-  After that, the user needs to open Dapp(D-Drive) and select the
files to upload.
-  Further, the AES algorithm link the user wallet address as a key
and encrypt the uploaded file. Payment dialogue box pop-ups
for the payment confirmation.
-  After the successful payment, the user’s file stored on the peerto-
peer network using IPFS protocol. IPFS returns a hash value
of the uploaded file, that will mapped with address using a smart
contract and get stored over a blockchain network.
-  Further, if the user want to share their uploaded file, they just
need to share the hash view with the other user, so that they
can view or download by clicking it.


## Testing

### Unit Testing:-

Unit Testing is a level of software testing where individual units/ components of a software are tested. The purpose is to validate that each unit of the software performs as designed. Various modules used in the system are tested individually through this testing. We had 3 modules in our project which are described as follows-

 1.  Blockchain Module: Testing was performed only on the working of the blockchain system to check if all the functionalities provided by blockchain system are running fine or not. Initially, we used Hyperledger Fabric for the blockchain network implementation and tested the system if we were able to do the transactions in the Blockchain Ledger.
**Status after testing - Success**

2.  Web + Data Storage Module: Testing was performed to check if all the functionalities are working fine on the front-end part of the website and if all the data involved in the system is storing on the local database or online distributed database accordingly.
**Status after testing - Success**

3.  Security Module: Testing was performed to check if the techniques like symmetric and asymmetric encryption used to enhance the security of the system are working fine and to check vulnerabilities in these techniques, if any.
**Status after testing - Success**

### Integration Testing:-

Integration Testing is a level of software testing where individual units are combined and tested as a group. The purpose of this level of testing is to expose faults in the interaction between integrated units. Above mentioned three modules are integrated together to check the compatibility of all three modules with each other. To do this, first of all security module was integrated with web + data storage module and then all the functionalities provided by these modules are tested.
**Status after testing - Success**

### System Testing:-
System Testing is a type of software testing that is performed on a complete, integrated system to evaluate the compliance of the system with the corresponding requirements. After integration testing, we searched for some other work around which can be used to integrate the Blockchain module with (web+security) module and we got to know that Hyperledger Composer can be used to integrate both the modules. Hyperledger Composer made the interaction between the web and Blockchain server smooth. All the functionalities provided by the system are working as per the requirements.
**Status after testing - Success**

## Project Snapshots

### 1) Metamask Login
<img width="161" alt="metamask" src="https://user-images.githubusercontent.com/101444257/174838723-6ecd6456-28bc-468f-b94a-3fc478794eff.png">

### 2) Account Balance Fetched

<img width="167" alt="ETHS" src="https://user-images.githubusercontent.com/101444257/174839723-d608a95a-3398-4d71-acd6-eac2d1e3d571.png">

### 3) User Interface
<img width="446" alt="user interface" src="https://user-images.githubusercontent.com/101444257/174841115-2c1767a7-564a-4f02-a9af-f78ba52e5186.png">

### 4) Payment Confirmation Dialog-Box
<img width="169" alt="payment " src="https://user-images.githubusercontent.com/101444257/174841804-cf686771-377a-4196-861b-e11947c93cc0.png">

### 5) File Uploaded With Hash Value

<img width="445" alt="file uploaded with hash value" src="https://user-images.githubusercontent.com/101444257/174842673-6861da75-57e7-4889-a167-2b1a9ef7ed96.png">


### 6) Hash Values of Uploaded Files

<img width="446" alt="hash values of uploaded files" src="https://user-images.githubusercontent.com/101444257/174843231-b354c65c-24df-4a5e-8ec8-0d155e95c53d.png">

### 7) Retrieving previously uploaded file using generated hash value

<img width="446" alt="Retrieving of file using generated hash value" src="https://user-images.githubusercontent.com/101444257/174845027-ba5266b5-ef8d-417e-bc4f-9f6b6d162845.png">




## Future Scope
This project has a very vivid future scope since decentralised safe storage of data is today’s biggest need.

### Project Upgradation
We have the project on our local host as of now, it is the first iteration of a working prototype. There is a lot of scope for improvement and upgradation.

- Project can be properly deployed on web.
- Openssl certificates could be deployed on the web server to make every transaction secure.


## Future scope of application
This project can be sold as a full fledged enterprise web based tool to conduct safe and secure data storage across various colleges and Universities as well companies across India, and overseas later. This project can find relevance and use in many other sectors such as-

- Healthcare sector to store confidential information of patients on a decentralised database.
- In human resource departments to store confidential information about employees.
- Police Department can use it to store very crucial information about the Criminals and Crime scenes confidentially Similarly almost every sector can use this product to store their sensitive data/information which needs high security.

## Installation Guide
- Install the required dependencies 
1) Nodejs 
   - Version(v9.10.0)
   - You can directly download from the website [Nodejs](nodejs.org/en/)
   
2) Truffle Framework
   - Version(5.1.39)
   - You can install truffle from your command line like this `npm install --g truffle@5.1.39` or from here [Truffle Framework](trufflesuite.com)
   
3) Ganache 
   - Compatible with any version
   - You can directly download from the website [Ganache](trufflesuite.com/ganache)
   
4) MetaMask
   - Compatible with any version
   - You can directly download from the website [MetaMask](https://metamask.io/)

Now open your command line terminal on your computer 

1. Create new folder 'Ddrive' using 'mkdir Ddrive'.
2. Enter Ddrive folder using 'cd Ddrive'.
3. Clone the Ddrive using 'git clone https://github.com/smita20BCS4643/D-Drive.git'
4. Enter the Ddrive using 'cd D-Drive'
5. Run command `npm install`
6. Make sure ganache is running 
7. Reset the migration using command `truffle migrate --reset`.
8. Now start the application using command `npm run start`
9. If the localhost is up and running, then kudos ;)

# Demonstration Video
Explanation and Demonstration [Demonstration Video](https://drive.google.com/file/d/13YJZClqjZBfbCFF3qw00PBUG3M654cAJ/view?usp=sharing)
   
     
 
