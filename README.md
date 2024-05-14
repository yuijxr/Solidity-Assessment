# Solidity-Assessment

This Solidity smart contract implements a basic token system called MyToken. It allows minting and burning tokens, along with maintaining token balances for addresses.

   - The contract defines public variables `tokenName`, `tokenAbbrv`, and `totalSupply` to store details about the token.
   - The contract defines a mapping `balances` to store token balances for addresses.
   - The contract provides a `mint` function to create new tokens and assign them to a specific address.
   - The contract includes a `burn` function to destroy tokens and reduce both the total supply and the balance of a specific address.
   - The `burn` function checks if the sender's balance is sufficient before burning tokens.

1. Deploy the `MyToken` contract to a supported blockchain network.
2. Interact with the contract using a compatible Ethereum wallet or development environment.
3. Use the `mint` function to create new tokens and assign them to specific addresses.
4. Use the `burn` function to destroy tokens and reduce both the total supply and the balance of specific addresses.
