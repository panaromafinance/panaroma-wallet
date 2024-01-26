# How to cancel Ethereum transaction?

Once a transaction has been confirmed and included in a block on the Ethereum blockchain, it becomes immutable and cannot be canceled or replaced. The window for canceling or modifying a transaction exists only while it remains in a pending state, awaiting confirmation.

Under normal circumstances, when the Ethereum network experiences low transaction volume, transactions are typically confirmed within seconds or minutes, leaving no time for cancellation. However, during periods of high network congestion, transactions may remain pending for extended periods, providing an opportunity to replace them before confirmation.

To attempt cancellation, users can send a new 0 ETH transaction to their own address with the same nonce as the previous transaction and a significantly higher transaction fee. This action might cancel the initial transaction, but success is not guaranteed and may not work consistently.

It's important to note that as of June 2021,  Panaroma Decentralized Wallet does not offer control over the 'nonce' setting for transactions, and therefore, the wallet app does not currently provide a direct way to cancel pending transactions. This feature is expected to be added in future updates.