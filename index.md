## Introduction to Solidity
#### 2022/07/08
#### Hiroyuki ONODA
---
## What is Solidity ?
Solidity is a statically-typed curly-braces programming language designed for developing smart contracts that run on Ethereum.
---
## Example
```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;
contract MyContract {
    function helloWorld() public pure returns (string memory) {
        return "Hello, World!";
    }
}
```
---
## Let's Deploy!
* compile using `solc`
* deploy
* run!
---
https://docs.alchemy.com/alchemy/tutorials/how-to-code-and-deploy-a-polygon-smart-contract#step-13-create-greet.js-to-interact-with-the-polygon-smart-contract
これにそって紹介する感じでいいか。

↑のコードはそのまま使いつつ、次の wagumi の紹介に繋げられれば。
