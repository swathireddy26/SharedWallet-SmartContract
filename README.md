# SharedWallet-SmartContract
1. This wallet contract can store funds and let users withdraw again.
2. One can also give "allowance" to other, specific user-addresses.
3. We can also restrict the functions to specific user roles.


# Project Diagram

<img width="1634" alt="Shared_wallet" src="https://user-images.githubusercontent.com/10496268/126773705-e53ca5dc-6c4d-45c3-ba0c-19647401c251.png">


# Reference:
https://ethereum-blockchain-developer.com/040-shared-wallet-project/00-overview/

# Tools needed:
Remix IDE for Smart contract development: https://remix.ethereum.org/

## How to write Smart Contract?
Go to the Remix IDE and create a new file with <Any_Name>. IDE automatically adds .sol extension to the file. 

## How to execute the Smart contract?
After successful compilation of the smart contract, head over to deploy and run transaction. There we see different environment options. 
We can deploy the smart contracts using 3 environments:

1. Injected web3 : It is provided by metamask or similar provider. This environment is little slow, becuase the transactions are mined every time we deploy or interact with contract.
2. Javascript VM : It is a simulated blockchain environment, that only exists in your browser. It is fast and easy to deploy.
3. Web3 provider : It establises connection to a software outside of the browser. We can connect to the local blockchain, uisng this environment.



