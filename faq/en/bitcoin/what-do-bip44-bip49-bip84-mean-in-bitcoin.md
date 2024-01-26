# What do BIP 44 /49 /84 mean in Bitcoin?

Bitcoin has three commonly used address formats for receiving payments, and  Panaroma Decentralized Wallet supports all three. This feature allows users to maintain separate Bitcoin balances and transactions for each format within a single multi-coin wallet. Essentially, a wallet created in  Panaroma Decentralized can function as three distinct Bitcoin wallets, each operating with a different address format, alongside other supported cryptocurrencies.

The emergence of multiple address formats stems from the increasing number of transactions on the Bitcoin network. Newer formats were introduced to reduce transaction sizes, enabling the network to process more transactions in each block.

Legacy Addresses:

- The oldest address format, often referred to as BIP44 format, typically begins with the number "1". Despite being the oldest format, most wallets support both receiving and sending payments to these addresses.

However, one drawback of using Legacy Addresses is the potential for higher transaction fees on the Bitcoin network. Sending a payment from a wallet that holds funds received in Legacy Address Format tends to incur higher fees compared to transactions using other formats.  Panaroma Decentralized Wallet's support for multiple address formats provides users with flexibility while considering transaction cost efficiency on the Bitcoin network.


Segwit Addresses:

- A more recent address format, referred to as BIP49 format, usually starts with the number "3". Supported by many newer wallet apps.

- Sending a payment from a wallet that operates with funds received to SegWit addresses is cheaper when compared to legacy addresses.


Native-Segwit Addresses

The newest address format referred to as BIP84 format, and the cheapest to work with when it comes to transacting on the Bitcoin network. The bech32 address format starts with "bc1".

An easy way to find out which format the wallet supports is to open the wallet app and check the first few symbols of the address for receiving Bitcoin.

On a practical level, apart from the difference in transaction fees, there is just one thing to keep in mind. Knowing the address format is also needed when restoring a Bitcoin wallet in some wallet app.

 Panaroma Decentralized wallet is able to both create and restore wallets operating in any of the three available address formats.

