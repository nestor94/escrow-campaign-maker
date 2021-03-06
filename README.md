# Escrow&Campaign Maker

Escrow&Campaign Maker is an application that allows:

- Creation of Escrow Contracts between two parties


### Escrow

Two parties can agree on a service offer/product selling, also, they will agree on an amount of Ether to sign the contract.

The buyer will deposit that amount into the contract, if the seller and buyer agreed on the status of the contract the seller will be able to withdraw the entire sum of Ether previously agreed.

If the buyer and seller disagreed, then the creator of the contract will be contacted to determine who has the correct claim, and then transfer the amount to the account.

### Stack

- Solidity
- Truffle
- React
- Bulma

### Run

- Install Global Depedencies:
>`npm install -g truffle ganache-cli`
- Install Project Dependencies:
>`npm install`
- Run tests
  - >`ganache-cli`
  - >`truffle test`

- Start Ganache CLI using an specific seed
>`ganache-cli -m 'Some testing accounts'`
- Deploy contracts on local network:
>`truffle migrate`
- Get ABI from Smart Contracts
>`npm run compile-contracts`
- Start Web Application
>`npm run start`
