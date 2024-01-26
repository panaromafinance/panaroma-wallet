# Why approve transaction is needed?

When engaging in certain swap trades, users are required to execute a separate "Approve" transaction. These include: 

ERC20 to ETH 

ERC20 to ERC20 

BEP20 to BNB 

BEP20 to BEP20 

The Approve transaction is a cost-effective action, serving as user permission for the DEX to deduct an approved amount of ERC20/BEP20 tokens to facilitate a trade. 

- Key points regarding Approve transactions: 

- Cost: Generally inexpensive to execute. 

- Purpose: Grants permission for the DEX to debit an approved amount of ERC20/BEP20 tokens for trade execution. 

- Amount Indication: Users can specify the amount of tokens the DEX is allowed to debit during the Approve transaction. 

- Advance Approval: Users can approve higher amounts in advance, anticipating future trades to avoid additional Approve transactions. 

- Failure Risk: Approving a lower amount than required by a trade will result in transaction failure. 

 
By understanding and managing Approve transactions appropriately, users can streamline the process and ensure the necessary permissions are in place for successful swap trades. 