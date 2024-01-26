# What is gas price and gas limit?

The fee on the Ethereum network is paid in Ether (ETH tokens) but is calculated in Gas units. 

 While it's not essential for users to grasp the concept of gas to understand transaction fees, for those curious, it is explained below. 

Gas serves as the fuel for executing actions on the Ethereum blockchain and is the unit used to calculate fees for specific actions, such as transactions. Two relevant parameters in determining the fee amount are associated with gas: 

Gas Limit: This is the maximum amount of Gas a user is willing to pay for confirming a transaction, with a minimum of 21,000. The typical gas limit for a transaction involving the transfer of ETH is 21,000. Wallet apps generally estimate the gas limit based on transaction complexity. An insufficient gas limit set for a transaction can lead to failure with an 'out of gas' error. 

Gas Price: This is the amount (in ETH) a user is willing to spend per unit of gas. Gas prices fluctuate with network conditions, being high during network congestion and low during idle periods. The higher the gas price a sender is willing to pay, the more prioritized the transaction becomes in the Ethereum network, as miners receive a higher reward. An insufficient gas price is often a reason for a transaction to remain pending for an extended period. 

Panaroma Decentralized estimates and sets both a limit and a gas price for each transaction on the Ethereum network. The recommended fee for the transaction is calculated by multiplying the recommended values for the gas limit and gas price. For example, if the gas limit is set at 50,000 units and the gas price is 20 Gwei (a subunit of Ether), it means that the sender is prepared to spend 0.001 ETH on the execution of the transaction 

 
