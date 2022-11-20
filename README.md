# Basic-Crypto-Token-Solidity-Smart-Contract

RC-20 defines tokens as blockchain-based assets 
that can be sent/received and have value. 
ERC-20 tokens are similar to Bitcoin and Litecoin in many aspects. 
However, the most significant difference is that instead of running on 
their own blockchain network, 
ERC-20 coins run on Ethereum’s blockchain network and use gas as the transaction fee.



Token smart contracts are not only responsible for creating tokens but also for handling transactions and keeping track of the balances of each token holder. To get some tokens one has to send some ETH to the token’s contract in return for allocated tokens.

ERC-20 is a standard or guideline for creating new tokens. The standard defines six mandatory functions that a smart contract should implement and three optional ones.

To start you can give your token a name, a symbol, and mention how dividable your token is, by specifying the decimals. ERC specifies a set of mandatory functions, which are a bit more complex and listed below:

totalSupply: A method that defines the total supply of your tokens, When this limit is reached the smart contract will refuse to create new tokens.
balanceOf: A method that returns the number of tokens a wallet address has.
transfer: A method that takes a certain amount of tokens from the total supply and gives it to a user.
transferFrom: Another type of transfer method which is used to transfer tokens between users.
approve: This method verifies whether a smart contract is allowed to allocate a certain amount of tokens to a user, considering the total supply.
allowance: This method is exactly the same as the approved method except that it checks if one user has enough balance to send a certain amount of tokens to another.

