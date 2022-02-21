# 🧬 Web3 Set Theory

Web3 Set Theory is an entities, conditions and rules based [informal set theory](https://en.wikipedia.org/wiki/Set_theory) based schema for constructing a Web3 Metaverse across EVM compute environments using native cryptographic Entity types: smart contracts, decentralized identifiers and future additions.

## Introduction

A Set is a collection of entities, conditions and rules. The entities must share similar properties and behaviors. The conditions define what "context" should be applied to entities. And finally rules relationships between entities contained within the set.

**All set schemas share the following core properties:**

- Entities
- Conditions
- Rules

The inherit simplicity, but also ability to define complex systems makes informal set theory a great candidate for mapping the emergent Ethereum metaverse.

Each Set type includes an entities, conditions and rules field, but each type has a unique Interfaces for the child items, which creates schema predictability across set types, but also flexibility as the system grows.

## Basic Set Examples

```yml
SmartContractSet
    entities
        smartcontract-1
    conditions
        condition-1
    rules
        rule-1
```

```yml
DecentralizedIdentifierSet
    entities
        did-1
    conditions
        condition-1
    rules
        rule-1
```

```yml
MetaSet
    entities
        set-smartcontract-1
        set-decentralizedidentifier-1
    conditions
        condition-all
    rules
        rule-all
```


### Minimal Smart Contract Set YAML Implementation
```yml
id: uniswap-swap-eth
name: Set (UniswapV2: Swap for ETH)
entities
    name: uniswapV2Router
    address: 0x7a250d5630B4cF539739dF2C5dAcb4c659F2488D
conditions
    function: swapExactTokensForETH(uint256,uint256,address[],address,uint256)
    arguments
        index: 1,
        type: bignumber,
        condition: gte,
        value: 10000000000000000000
```


## Demonstrations

| About  | Application |
| ------------- | ------------- |
| <p>Quick introduction to Web3 Set Theory using example and demo quests implementing a conditions/rules validations library to compare transactions to SmartContract set conditions and rules. </p>  | <p><img src='https://github.com/web3-set-theory/.github/blob/main/profile/app.jpeg?raw=true' align="right" width="380px" ></p><br/><p><span>[EthDenver Demo Application](https://web3-set-theory.github.io/)</span></p> |


## Libraries

### Schema ([Module](https://github.com/web3-set-theory/schema))
The Web3 Set Theory schema defines a simple, but extensible interface for applying information set theory to Web3 entities.

The primary objective is to contextualize relationships between different Entity types in varying EVM compute environments using a simple off-chain set based schema to organize the who, what, when, where, how... and why.


<!-- Quick introduction to Web3 Set Theory using example and demo quests implementing a conditions/rules validations library to compare transactions to SmartContract set conditions and rules.  -->

<!--
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

<!-- 
<p>A Set is a collection of entities, conditions and rules. The entities must share similar properties and behaviors. The conditions define what "context" should be applied to entities. And finally rules relationships between entities contained within the set</p> -->