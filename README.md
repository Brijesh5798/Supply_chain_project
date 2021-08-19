# Supply_chain_project

## Truffle Version
truffle@4.1.14

## Node Version
v14.17.0

## Web3 Version
v1.5.1

## Contract Address
FarmerRole :- 0xAd5e72F45C337100152bdb185f7db1BFbeFEd594
DistributorRole :- 0x3B2d1a6cAF9a159590b5f4C65CFcF7D6D4EF6378
RetailerRole :- 0xEfb85ADa6994743E6360AE2b4238a8A95c257D69
ConsumerRole :- 0xfBd1b19E2169e57963C7086a9559656E68a833Bd
SupplyChain :- 0x93321f81548c66Ab3823C1924c04b14Ad7761240

## Requirement 2: Project write-up - Libraries
I used one library called Roles which made it easier to manage AccessControl in my DAPP. It made it easy to add and remove roles in each of my AccessControl contracts

## Requirement 3: Project write-up - IPFS
I did not use IPFS to deliver my website for this project

# Getting Started
These instructions will help you to compile,test and run my project

## Prerequisites
Please make sure you've already installed ganache-cli, Truffle and enabled MetaMask extension in your browser.

## Installing
Clone this repository:
git clone https://github.com/Brijesh5798/Supply_chain_project.git

Change directory to project-6 folder and install all requisite npm packages 
cd project-6
npm install

Launch Ganache:
ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster"

In a separate terminal window, Compile smart contracts:
truffle compile

Test smart contracts:
truffle test

In a separate terminal window, launch the DApp:
npm run dev