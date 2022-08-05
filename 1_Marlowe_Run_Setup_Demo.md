# Marlowe Run Interaction with Daedalus wallet on Testnet

In this exercise, we will be looking at Marlowe Contracts using Marlowe Run. 
We will need to perform the below steps in order to do this.


### Download the Daedalus installer
Use one of these links to install a Daedalus wallet connected to the pioneers network:

 #### Install Daedalus for Marlowe Testnet
- Linux (https://pioneers.marlowe-finance.io/daedalus/linux)
- Mac (https://pioneers.marlowe-finance.io/daedalus/macOS)

- Change the downloaded file to executable, and run the file.
- Daedalus for Marlowe will be installed in your system.
- Sync Daedalus to the testnet (will take a long time!)

#### Get some TestADA from the faucet
```
#Note:  $ADDRESS is the address of the wallet you want to fund
curl -XPOST https://faucet.pioneers.testnet.marlowe-finance.io/send-money/$ADDRESS 
```
#### Create 3 wallets (Marlowe1, Marlowe2, Marlowe3) using Daedalus
  NOTE: don't forget to backup the seed phrases for all the 3 wallets!

#### Transfer some funds from the first wallet to the other 2 wallets using Daedalus

#### Once Daedalus is synced, you can start with Marlowe Run from the below link
Visit http://marlowe-run-marlowe-pioneers.plutus.aws.iohkdev.io/

