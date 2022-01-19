=======
Wallets
=======

Foundations
===========
- A wallet is a piece of software that holds a user's funds
- Every wallet can be referred to by a unique identifier called an "address"
- An address looks like this: ``0x59b7a8eB6A30746A08a562FDE048c832E51A65dd``
- An address is a hexadecimal representation of an account's location in block chain storage
- Addresses are 20 bytes long (40 characters)
- Wallets utilize public key cryptography
- Every wallet has a private key
- Every wallet address is a public key
- When a new account is created users are often given a "seed phrase" associated with an account
- A "seed phrase" is a mnemonic phrase that can be used to generate a private key
- If a wallet's private key or seed phrase is compromised whoever has access to either can completely control the wallet
- A wallet can be used to send signed (authenticated) transactions to the blockchain

Creating a wallet
=================

Currently the most popular wallet for DeFi is called Metamask.  

In this example we will install metamask.

Installing Metamask
-------------------

1. Install metamask: https://metamask.io/
2. Follow prompt to create a new account
3. Write down seed phrase on a piece of paper
4. Write down your seed phrase again on another piece of paper
5. Keep both pieces of paper in a safe and private location
6. Delete your metamask account
7. Restore your account using the seed phrase (this is done to make sure you've written down the seed phrase correctly)
8. Fund your account

.. note::
    If you lose your seed phrase or anyone else obtains a copy of this all of your funds can be lost or stolen.
    
.. note::
    Never write out your wallet address. You should only ever copy and paste addresses.

Funding your wallet
-------------------
Options:  

- Send ethereum to your wallet address from a custodial/centralized exchange such as Coinbase or Binance
- Purchase ethereum through `localcryptos <https://localcryptos.com/Ethereum/>`_
- Have a trusted friend send you ethereum via Tornado Cash from an anonymized wallet

.. note::
    Every transaction you make using your wallet is recorded forever on the blockchain.

.. note::
    If you fund your DeFi wallet using a centralized exchange (cex) and you've verified your identity your new wallet will be associated with your identity and your wallet will not be anonymous.
