## info.honeyswap.org

A uniswap.info fork for Honeyswap. It can be viewed at [info.honeyswap.org](https://info.honeyswap.org).

### Subgraphs

The fork is powered by forks of two subgraphs:

- [Uniswap v2 Subgraph](https://thegraph.com/explorer/subgraph/1hive/uniswap-v2): A fork of the official Uniswap v2 subgraph with adjustments to use xDai as the base currency and a modified set of whitelisted tokens. Source code can be found [here](https://github.com/1Hive/uniswap-v2-subgraph).
- [Ethereum Blocks](https://thegraph.com/explorer/subgraph/1hive/xdai-blocks): A fork of the Blocklytics Ethereum Blocks subgraph with no modifications, deployed for xDai. Source code can be found [here](https://github.com/1Hive/ethereum-blocks).

### Front-end

The front-end is a fork of the official uniswap.info source code with modifications to use Blockscout instead of Etherscan along with minor adjustments to use the appropriate token lists and factory addresses.

The source code for the front-end can be found [here](https://github.com/1Hive/honeyswap-info).
