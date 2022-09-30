### Standard BEP20 Contract

- Unflatten contract, ready to be consumed for fresh project using BEP20 standard

💡 Use [Flattener Plugin](https://github.com/bunsenstraat/flattener) to flatten the build code
💡 Example when deploying new token:

```solidity
// SPDX-License-Identifier: UNLICENSED
pragma solidity ^0.8.0;
import "./BEP20.sol";

contract MyToken is BEP20Token {
    constructor() BEP20Token(<token_name>, <symbol>, <decimal>, <total_supply>) {
    }
}

```
