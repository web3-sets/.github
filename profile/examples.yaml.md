
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
    target: function
    signature: swapExactTokensForETH(uint256,uint256,address[],address,uint256)
    arguments
        index: 1,
        type: bignumber,
        condition: gte,
        value: 10000000000000000000
```
