## Introduction to Solidity and Wagmi Library
#### 2022/07/08
#### Hiroyuki ONODA
---
## What is Solidity ?
Solidity is a statically-typed curly-braces programming language designed for developing smart contracts that run on Ethereum.
---
## Smart contract
https://ethereum.org/ja/developers/docs/smart-contracts/

>  A "smart contract" is simply a program that runs on the Ethereum blockchain. It's a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain.
---
## Code Example
```solidity
//SPDX-License-Identifier: Unlicense
pragma solidity ^0.8.0;
contract Greeter {
    string private greeting;

    constructor(string memory _greeting) {
        greeting = _greeting;
    }
    function greet() public view returns (string memory) {
        return greeting;
    }
    function setGreeting(string memory _greeting) public {
        greeting = _greeting;
    }
}
```
---
## どうやって開発するの？
https://docs.alchemy.com/alchemy/tutorials/how-to-code-and-deploy-a-polygon-smart-contract

いい記事があったので、これに沿って説明していきます。(手抜き)

https://github.com/onoda-cg/polygon-smart-contract-tutorial
---
## Wagmi React Hooks for Ethereum

https://wagmi.sh/
---
## 使用例
先程のGreetコントラクトとのやり取りをWagmi Library+Reactで実装してみる

https://github.com/onoda-cg/wagmi-sample-app
---
## まとめ
* Solidityについて実装方法に沿って説明した
* Wagmi Libraryの紹介と、サンプルの提示

