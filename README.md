# PatientMedchain: A secure patient-centered EHR (Electronic Health Record) decentralized application using blockchain

## Introduction
This project aims to provide an application to enable the patient to have control over access to their health records. The patient can grant and revoke doctors' access to their health records. Then, doctors with granted access can add health records for patients and patients can view their health records.

## Installation
The project needs Node.js and npm to work. I've included the required installed dependencies below.

### Node modules
1. Go to [the Node.js](https://nodejs.org/zh-cn) website to Download the Node.js
2. Locate the project on your computer and Run "npm install" to install the required dependencies.

### Ganache
Go to [Ganache website](https://archive.trufflesuite.com/ganache/) to download Ganache

### Truffle and Smart Contract
1. Install truffle by running "npm install truffle -g"
2. Compile Contracts by running "truffle compile"


## Configuration

### Ganache
1. Create a workshop on Ganache and upload the "truffle-config.js" file to truffle projects
2. User Server tab:
   Set Hostname to 127.0.01 -lo
   Set the Port Number to 7545
   Set Network ID to 5777
   Select Automine and Error on transaction failure

### MetaMask
1. Install MetaMask Chrome Extension
2. Create a network on MetaMask to connect the Ganache
   Set New RPC URL to Ganache RPC SERVER's value
   Set the Currency symbol to ETH

## Running the application
1. Navigate to /YOUR PROJECT DIRECTORY/client/ on terminal
2. Run "npm start"

### Connect MetaMask to the local blockchain
Connect the MetaMask to localhost:3000
Click on "Import account"
Select an address from ganache and copy its private key to import the account to MetaMask.
<img width="1194" alt="Screenshot 2024-09-09 at 1 55 33 PM" src="https://github.com/user-attachments/assets/64f560af-0e68-4139-9012-b76d5fb1144e">

