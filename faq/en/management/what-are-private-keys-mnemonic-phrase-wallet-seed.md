# What are private keys?

In the cryptocurrency context, terms such as private key, mnemonic phrase, secret phrase, and wallet seed are often used interchangeably. These terms collectively refer to information essential for controlling funds within non-custodial cryptocurrency wallets like Panaroma Decentralized. 

During the setup of any non-custodial cryptocurrency wallet, including Panaroma Decentralized, users are provided with a private key. This key, presented in the form of 12 or more plain English words (referred to as a secret phrase in the case of Panaroma Decentralized), grants the user access and ownership over all assets within the wallet. Unlike traditional services allowing password recovery, non-custodial wallets, when built properly, do not offer the capability to recover private keys. 

Private keys are randomly generated on the user's device during wallet creation and never leave the device afterward. If the user deletes the wallet, the keys are also deleted. Therefore, recovering a private key from an external source becomes impossible if the user cannot access it on the device. 

It is imperative for users to back up their private keys during wallet setup. Most wallets prompt users to record a copy of the private key immediately after wallet creation. 

Panaroma Decentralized creates a unique private key, referred to as a secret phrase, for each multi-coin wallet. This secret phrase, consisting of 12 plain English words, allows users to: 

- Restore access to the existing wallet even if the Panaroma Decentralized wallet app is deleted from the phone. 

- Restore access to the same wallet but in a different wallet app. 

In addition to the secret phrase, Panaroma Decentralized displays other options, including EVM Private Key, BIP32 Root Key, Account Extended Public Key, and Account Extended Private Key. These options represent various representations of the same secret phrase, and users only need to back up the secret phrase. 

  

Specifically: 

- EVM Private Key enables the import of EVM-based cryptocurrencies to other standard-compliant wallet apps. 

- BIP32 Root Key is another representation of the secret phrase, providing full control over wallet assets. 

- Account Extended Public Key allows read-only monitoring of Bitcoin and other UTXO-based cryptocurrencies on the respective wallet. 

- Account Extended Private Key, similar to Account Extended Public Key but with ownership capabilities, facilitates the import of Bitcoin and other UTXO-based cryptocurrencies to other compliant wallet apps. 

It's crucial not to share EVM Private Key, BIP32 Root Key, Account Extended Public Key, or Account Extended Private Key publicly, as unauthorized access could lead to potential security risks. Each of these keys serves specific purposes and relates to different types of cryptocurrencies within the wallet. 
