# SharedWallet-SmartContract
1. This wallet contract can store funds and let users withdraw again.
2. One can also give "allowance" to other, specific user-addresses.
3. We can also restrict the functions to specific user roles.


# Project Diagram

<img width="1634" alt="Shared_wallet" src="https://user-images.githubusercontent.com/10496268/126773705-e53ca5dc-6c4d-45c3-ba0c-19647401c251.png">


# Reference:
https://ethereum-blockchain-developer.com/040-shared-wallet-project/00-overview/

# Tools needed:
1. Remix IDE for Smart contract development: https://remix.ethereum.org/
2. Metamask browser extension for using Injected Web3 environment: https://metamask.io/
3. Ganache By truffle for using Web3 Provider extension: https://www.trufflesuite.com/ganache

## How to write Smart Contract?
Go to the Remix IDE and create a new file with <Any_Name>. IDE automatically adds .sol extension to the file. 

## How to execute the Smart contract?
After successful compilation of the smart contract, head over to deploy and run transaction. There we see different environment options. 
We can deploy the smart contracts using 3 environments:

1. **Injected web3 :** It is provided by metamask or similar provider. This environment is little slow, becuase the transactions are mined every time we deploy or interact with contract.
2. **Javascript VM :** It is a simulated blockchain environment, that only exists in your browser. It is fast and easy to deploy.
3. **Web3 provider :** It establises connection to a software outside of the browser. We can connect to the local blockchain, uisng this environment.

Injected web3
-------------
1. To use this, we need to install Metamask browser extension
2. Buy some Ethers from any test networks like Goerli, Rinkeby using Faucet
3. Once remix connects to the Metamask, we will see the account address of test network that we connected to, in the deploy and run transaction page of Remix.
4. Deploy the contract by making transaction through metamask.
5. go to the remix IDE 
6. go to "Deployed Contracts"
7. select the contract and interact with it using the buttons

Javascript VM 
-------------
1. select the "contract" in the contract tab 
2. just "Deploy" the contract
3. go to "Deployed Contracts" section
4. select the contract and interact with it using the buttons 


web3 provider
-------------
1. To use this, we need to install ganache truffle (It is a personal blockchain for rapid ethereum and corda distributed application development). 
2. when we select web3provider environment option in Remix IDE, it will ask for "Web3 Provider Endpoint". Copy the RPC adress (http://127.0.0.1:7545) from the ganache and supply it here.  
3. when we click on okay, we can see all the available accounts of local ganache blockchain in Remix IDE.
4. Deploy the smart contract and interact with it either from Remix IDE or from truffle suite. All the transactions will be logged in the Ganache.



