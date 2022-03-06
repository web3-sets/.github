# 🧬 Web3 Set Theory

Web3 Set Theory is an entities, conditions and rules based [informal set theory](https://en.wikipedia.org/wiki/Set_theory) based schema for constructing a Web3 Ethereum Metaverse across EVM compute environments native cryptographic Entity types: smart contracts, decentralized and  identifiers.

https://web3-set-theory.github.io

### Hypothesis

EVM compute environments are expanding and all evidence is pointing to continued growth and propagation of EVM compute environments. Between, sidechains like Polygon/Avalanche and L2s like Aribitrum/Optimism we are already experiencing the outgrowth of Ethereum mainnet into new EVM compute state - protocols with varying security implementations and finality guarantees.

The complexity to manage the outgrowth of EVM computes will grow exponentially.

A formal system to capture the "meta state of all EVM compute environments" is required to successfully moved forward in the Ethereum Cambrian Era.

### How
Using a formal specification (JSON Schema) a `EVMState` and `Web3EntitySet` validation engine has been implemented to facilitate the expression of informal set theory across interconnected EVM compute environments. The schema defines how to structure Web3 Entity relationships and state condition matching with a flexible rule based system.

### Why

The secondary effect of the EVMState/Web3EntitySet validation engine is a "MultiChain Web3 Metaverse Questing Protocol" which can capture expressive user journeys in an Ethereum ecosystem via machine-readable instruction sets.

The first iteration of Web3 Set Theory will include 3 Entity types: 

- Smart Contract (Web3 Entity)
- Decentralized Identifier (Web3 Entity)
- Meta (Protocol Entity)

Both the `SmartContract` and `DecentralizedIdentifier` entities are Web3 native cryptographic entities.

The `Meta` entity is not a Web3 entity, but instead a Set Theory construction used to organize "sets of sets" and to facilitate the full expression of set theory that can scale to fully express all possible relationships defined across all EVM compute environments.

A Meta set (Set to contain Sets) can link together `SmartContract` and `DecentralizedIdentifier` sets. Meaning Entities that have different cryptographic primitives can still be formally linked together in a unified set and validated together. Put simply, a set can express both that a user needs to interact with a smart contract in a specific way and that same user must also complete an action with a decentralized identifier in a specific way.

# Modules

The Web3SetTheory system is currently comprised of two primary modules: schema and validation.

## Schema ([Module](https://github.com/web3-set-theory/schema))

The `@web3-set-theory/schema` node module defines Web3 Set Theory schema in JSON Schema and interface via Typescript.

![CI](https://github.com/web3-set-theory/schema/actions/workflows/main.yml/badge.svg)
![ts](https://badgen.net/badge/-/TypeScript?icon=typescript&label&labelColor=blue&color=555555)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)

## Validation ([Module](https://github.com/web3-set-theory/validation))

The `@web3-set-theory/validate` node module validates EVMState and Web3EntitySets via implementation of `@web3-set-theory/schema`. 

![CI](https://github.com/web3-set-theory/validation/actions/workflows/main.yml/badge.svg)
![ts](https://badgen.net/badge/-/TypeScript?icon=typescript&label&labelColor=blue&color=555555)
[![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html)

## Applying Set Theory to Web3 Entities

The objective of Web3 Set Theory is to formalize a machine-readable instructions for creating relationships across and between Web3 entities.

Or more simply put, Web3 Set Theory helps to contextualize User journeys in decentralized environments by connecting actions/steps between resources like smart contracts and third-parties like decentralized identifiers. Inspired from the scalability of formal set theory and approachability of informal set theory, Web3 Set Theory takes aim at solving the complex problem of defining and formalizing relationships across digital resources and assets in a constantly evolving landscape.


## Demonstrations

| About  | Application |
| ------------- | ------------- |
| <p>Quick introduction to Web3 Set Theory using example and demo quests implementing a conditions/rules validations library to compare transactions to SmartContract set conditions and rules. </p>  | <p><img src='https://github.com/web3-set-theory/.github/blob/main/profile/app.jpeg?raw=true' align="right" width="380px" ></p><br/><p><span>[Demo Application](https://web3-set-theory.github.io/)</span></p> |
