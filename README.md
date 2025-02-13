# Block-Chain Based Voting System

***BlockVote*** is a blockchain-based voting app created in React and Solidity.

## Project Description

***BlockVote*** is an online voting platform built on **Ethereum blockchain technology**, which offers a **transparent**, **decentralized**, and **tamper-proof** ledger. By addressing the challenges of traditional voting systems, blockchain enhances security, trust, and efficiency. This platform allows eligible voters to cast their votes for their preferred candidates and view the results once the election concludes. It is faster, more secure, and more cost-effective compared to conventional voting methods. Some of the standout features of our system include:

a) Decentralized & Transparent

b) Trustful

c) Immutable

This project serves as a foundational implementation of a voting system aimed at exploring the fundamentals of Ethereum blockchain technology and the operational principles of decentralized applications built with **Solidity** and **React**. In this system, the account responsible for deploying the **smart contract acts as the Admin**, who has the authority to add eligible voters and candidates. Once the Admin initiates the election, **authorized voters can cast their ballots** for their preferred candidates. After the Admin concludes the election, the final results are instantly visible to the voters.

## Installation

### Step 1: Clone the Project
```git clone https://github.com/vatsal-30/voting-Dapp.git```

### Step 2: Start Ganache
Open the Ganache GUI client to start the local blockchain instance.

### Step 3: Compile and Deploy Election Smart Contract
```truffle migrate --reset```
We must migrate the election smart contract each time restart ganache.

### Step 4. Configure Metamask
- Unlock Metamask
- Connect metamask to the local Ethereum blockchain provided by Ganache.
- Import an account provided by Ganache.

### Step 5. Run the Front End Application
```
cd .\client
npm install
npm start
```
Visit the URL in your browser: http://localhost:3000

## Snapshots

<img width="947" alt="Admin" src="https://github.com/vatsal-30/voting-Dapp/assets/100423588/f77eac5f-cc35-495b-ba04-3ebe62e1d602">
<img width="960" alt="index" src="https://github.com/vatsal-30/voting-Dapp/assets/100423588/8caf0e92-6107-4a9c-855b-05b269ad9023">
<img width="960" alt="vote" src="https://github.com/vatsal-30/voting-Dapp/assets/100423588/ab7016d0-1b80-4763-bc76-d9525c46ad00">



