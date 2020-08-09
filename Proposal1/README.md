# DeFi DAO  based Future & Options

## Basic Defintions 

 **F&O** Future and Options represents Derivatives of Stock Market.These Derivatives are the financial instruments deriving their values from an underlying such as currency, gold, or the stocks of a company.

**DAO** (Decentralized Autonomous Organization) is an organization represented by rules encoded as a computer program that is transparent, controlled by the organization members and not influenced by a central government.

## ![](https://github.com/Parizval/DeveloperDock/blob/master/srs/target.png) Objective of the Proposal  

The purpose of the project is to create a decentralized online **Options** platform on tezos blockchain. 

## ![](https://github.com/Parizval/DeveloperDock/blob/master/srs/policy.png) Description  of  the  Proposal

Proposal aims to develop a decentralized platform for f&o trading which could utlized by anyone around the globe. Most of the platforms are centralized and governed by a single authority.  
This leads to serveral inefficies and drawbacks in the current platforms such as: 
 
 - Data is being fetched from a single source. 
 
 -  Central Monitoring  
 
## How do we solve such problems ? 
 
 - We plan to make the trading process much more transparent with the help of the blockchain.
 
 - Decentralized network of trusted oracles have proven to give much more reliable information. 
 
 - Premium Calculation for trading on smart contracts make the process transparent and removes hidden costs while trading.

## ![](https://github.com/Parizval/DeveloperDock/blob/master/srs/process.png) Workflow 

- Users would be register/login with the help of magic auth. 

- Functions such as **PUT** and **CALL** would be present on the dashboard of the platform along with the realtime pricing.

- Transactions to pay premium would be done with the help of AirGap/Thanos Wallet. 

- Details of the trade would be sent to the smart contract. 

- User would also be able to view his past trades. 

- Smart contract functions would be responsible for calculating the premium decay which makes the process of trading much more transparent. 

## ![](https://github.com/Parizval/DeveloperDock/blob/master/srs/timeline.png) Timeline 

| Week  | Target |
| ------------- | ------------- |
| Week 1   | Work on FA 1.2 and Options Contract ( Call and Put Options)  |
| Week 2  | Testing and Integration with Thanos Wallet, quipuswap and work on the oracles to feed the data |
| Week 3  | Developing the front end and user interface of the application |
| Week 4  | Integration of smart contracts with the front ends and testing of the platform. |
| Week 5  | Improving the functionality and fixing bugs |
| Week 6  | Deployment and monitoring of the applicaiton |

## Technology Stack 

 - React - Front End
 
 - NodeJs - Backend  
 
 - Smartpy -  Smart Contracts 
 
 - Taquito / Conseiljs  - Smart Contract Interaction 
 
 - Oro - Using to get the BTC/USD price

