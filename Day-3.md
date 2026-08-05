# Day 3: EVM Primitives & Foundry Deployment Mechanics

## Summary
Successfully set up a clean development environment from scratch, resolved local tooling issues, and completed my first real deployment of a smart contract on a local blockchain.

## Key Learnings
- **Tooling Constraints:** Solved environment/path collision bugs inside Git Bash on Windows.
- **EVM Interaction:** Compiled a local Solidity contract to bytecode using `forge build`.
- **State Broadcast:** Learned the critical role of the `--broadcast` flag to move from a local simulation (dry run) to an actual on-chain transaction deployment using Anvil.
- **Contract Calls:** Interacted directly with the deployed state variable through local RPC nodes using `cast call`.

## Code Example Developed
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.13;

contract HelloWorld {
    string public greet = "HOLA MUNDO!";
}
```

## Tools Used
- **Foundry / Anvil / Cast**
- **Solidity ^0.8.13**
