## Honeymaker

Honeymaker is a SushiMaker deployment and accompanying bot that converts LP shares on Honeyswap into Honey for the Honey Common Pool.

### Contracts

#### `SushiMaker`

SushiMaker is deployed at [`0x076b64f9F966e3bBD0FCdC79D490Ab71cF961bb0`](https://blockscout.com/poa/xdai/address/).

##### Compilation options

- **Compiler version**: `0.6.12+commit.27d51765`
- **EVM version**: Compiler default
- **Optimzation**: No
- **SushiMaker version**: [84243d745ed68d76c85964eb4a160211cecf0c88](https://github.com/sushiswap/sushiswap/blob/84243d745ed68d76c85964eb4a160211cecf0c88/contracts/SushiMaker.sol)

##### Constructor arguments

- `_factory`: [`0xA818b4F111Ccac7AA31D0BCc0806d64F2E0737D7`](https://blockscout.com/poa/xdai/address/0xA818b4F111Ccac7AA31D0BCc0806d64F2E0737D7) (Honeyswap Factory)
- `_bar`: [`0x05e42c4ae51ba28d8acf8c371009ad7138312ca4`](https://blockscout.com/poa/xdai/address/0x05e42c4ae51ba28d8acf8c371009ad7138312ca4) (Common Pool)
- `_sushi`: [`0x71850b7e9ee3f13ab46d67167341e4bdc905eef9`](https://blockscout.com/poa/xdai/address/0x71850b7e9ee3f13ab46d67167341e4bdc905eef9) (Honey)
- `_weth`: [`0xe91d153e0b41518a2ce8dd3d7944fa863463a97d`](https://blockscout.com/poa/xdai/address/0xe91d153e0b41518a2ce8dd3d7944fa863463a97d) (WXDAI)

### Bot

The bot periodically calls the `convert` function on the SushiMaker contract for selected pairs on Honeyswap to convert the LP shares to Honey.

The source code for the bot can be found [here](https://github.com/1hive/honeymaker).
