# How can you send Bitcoin transactions that can't be spent until a certain date?

The Panaroma Decentralized wallet introduces an experimental feature that allows users to send Bitcoin transactions with a specific time lock, preventing the recipient from spending the funds until a predetermined date in the future. This feature, while available on the Bitcoin blockchain, is not commonly implemented by many wallet applications.

Users interested in utilizing this experimental feature need to manually activate it by navigating to Settings >> Experimental Features within the Panaroma Decentralized wallet application.

Once a transaction with a time lock is confirmed on the blockchain, the recipient technically becomes the owner of the funds, but they are unable to spend the funds until the specified time has passed. To indicate this, the Panaroma Decentralized wallet application displays a lock symbol next to the balance amount associated with transactions featuring time locks.

It's crucial to note that for the recipient to correctly interact with and spend funds from such transactions, they must be using the Panaroma Decentralized wallet version 0.10 or a higher version. Additionally, the BIP44 address format for Bitcoin should be employed. Other wallet applications may not be able to accurately identify or handle transactions with time locks on the network, potentially leading to the transactions being unrecognized or overlooked. Therefore, compatibility with the Unstoppable wallet version and adherence to the BIP44 address format are essential for proper functionality and visibility of transactions with time locks.
