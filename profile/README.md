# Welcome to TON Connect

_TON Connect_ enables communication between _wallets_ and _apps_ in the TON ecosystem.

## Table of contents

* [TON Connect Overview](https://docs.ton.org/develop/dapps/ton-connect/overview)
* [Protocol specifications](https://docs.ton.org/develop/dapps/ton-connect/protocol/)
* [Integrate a wallet](https://docs.ton.org/develop/dapps/ton-connect/wallet)

## Why TON Connect?

TON blockchain enables creation of trust-minimized applications and services at a massive scale.

**Apps** provide the UI to an infinite range of functionality in TON based on smart contracts, 
but do not have immediate access to users’ funds. Therefore they are often called decentralized apps or “dapps”.

**Wallets** provide the UI to approving transactions and hold users’ cryptographic keys securely on their personal devices.

This separation of concerns enables rapid innovation and high level of security for the users: 
wallets do not need to build walled-garden ecosystems themselves, while the apps do not need to take the risk holding end users’ accounts.

TON Connect is a bridge that crosses this conceptual gap.

## Objectives

1. Users get a familiar and friendly experience across all TON dapps.
2. Any app can be operated by any wallet.
3. Apps do not need to maintain their own backend to receive data from the wallets.
4. Apps could use an all-in-one SDK to establish connection with the wallet. 
   * SDK takes care of re-connection, supports switching between multiple accounts and ships with UI controls.
   * SDK also transparently works with a JS bridge for embedded dapps and browser extensions.
5. Each wallet maintains their own bridge server and are free to choose how to communicate with it.



