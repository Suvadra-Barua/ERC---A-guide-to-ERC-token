# ERC---A-guide-to-ERC-token
## What is ERC?
- Full form is Ethereum Request for Comment
- It decribes application-level standards and conventions in the Ethereum ecosystem.
- It includs contract standards such as token standards (ERC-20), name registries (ERC-137), URI schemes (ERC-681), library/package formats (EIP190), and wallet formats (EIP-85).
After all,It's fixed a standard to maintain when developing an dapp in ethereum
## Some Terminology
#### Native Token
The token or cryptocurrency of a blockchain. Example: Bitcoin is the native token of Bitcoin blockchain, Ether is the native token of Ethereum blockchain.
#### Token / Crypto Token
It is the token of a platform where that platform build on a blockchain.
Example: Cryptokitties is a DApp that build on Ethereum blockchain. Here, Cryptokitties use a token which also named cryptokitties. The token cryptokitties is  used to run cryptokitties dapp. 
#### Fungible
One is equal to the other. For example, one dollar is always equal to another dollar.
#### Non-fungible
One is not equal to another. For example, artworks. If we traded one for another we are not getting equal value. Each non-fungible item is unique.
#### Spender
An address that gets approved by the token owner. Spenders are approved to spend a specified amount of tokens (with fungible tokens) or approved to spend a specific token (in the case of non-fungible tokens) on behalf of the user. I.E: the user may approve the spender once and the spender may spend on the user’s behalf until their allowance is finished.

## Token Standard
#### ERC-20
**Author :** Fabian Vogelsteller, Vitalik Buterin
**Functionality :** The following standard allows for the implementation of a standard API for tokens within smart contracts. This standard provides basic functionality to transfer tokens and allow tokens to be approved so they can be spent by another on-chain third party. A standard interface allows any tokens on Ethereum to be re-used by other applications: from wallets to decentralized exchanges.
