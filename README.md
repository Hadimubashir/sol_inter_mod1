
# HI Token Contract

This is a simple ERC-20 compatible token contract named HI.

## Overview

The contract provides basic functionalities to mint and burn tokens. It keeps track of the supply and individual balances of addresses.

## Features

- **Minting:** Tokens can be created and assigned to an address.
- **Burning:** Tokens can be destroyed, reducing the overall supply.

## Usage

### Deployment

1. Deploy the contract on a supported Ethereum Virtual Machine (EVM) such as Remix or Truffle.
2. Use a compatible wallet (e.g., MetaMask) to interact with the deployed contract.

### Interacting with the Contract

#### Minting Tokens

```solidity
function mint(address _address, uint _value) public {
    // ... (Add details on how to call this function)
}
```

#### Burning Tokens

```solidity
function burn(address _address, uint _value) public {
    // ... (Add details on how to call this function)
}
```

### Notes

- Ensure the provided address has sufficient balance before burning tokens to avoid errors.

## License

This contract is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---
