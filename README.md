# Base Fee Provider

On supported networks, this contract reads block.basefee and reports it for interpretation by the [base fee oracle](https://github.com/yearn/yearn-vaults/blob/master/contracts/BaseFeeOracle.sol). The latest version of this oracle contract can also be found in this repo.

BaseStrategy versions prior to 0.4.5 hardcode an earlier version of the base fee oracle (termed legacy below) that also has a hardcoded base fee provider address.

## Current Deployments (v0.1.0)

| Chain    | Contract | Deployment Address                         |
| -------- | -------- | ------------------------------------------ |
| Ethereum | Provider | 0xe0514dD71cfdC30147e76f65C30bdF60bfD437C3 |
| Ethereum | Oracle   | 0x1E7eFAbF282614Aa2543EDaA50517ef5a23c868b |
| Fantom   | Provider | 0x95F256488861e055231E8F57c107E773c95E221b |
| Fantom   | Oracle   | 0xa11E8b010164C1B58b43527D0fDD369845d6ec4A |
| Arbitrum | Provider | 0x1ba4eB0F44AB82541E56669e18972b0d6037dfE0 |
| Arbitrum | Oracle   | 0x50D5D1e53C62Eb7E642748eF32231f88A1680F33 |
| Optimism | Provider | N/A                                        |
| Optimism | Oracle   | 0xbf4A735F123A9666574Ff32158ce2F7b7027De9A |

## Legacy Deployments

| Chain    | Contract | Deployment Address                         |
| -------- | -------- | ------------------------------------------ |
| Ethereum | Provider | 0xf8d0Ec04e94296773cE20eFbeeA82e76220cD549 |
| Ethereum | Oracle   | 0xb5e1CAcB567d98faaDB60a1fD4820720141f064F |
| Arbitrum | Provider | 0xFf72f7C5f64ec2fd79B57d1A69C3311C1bB3EEF1 |
| Arbitrum | Oracle   | 0xdF43263DFec19117f2Fe79d1D9842a10c7495CcD |
| Optimism | Provider | 0x46679Ba8ce6473a9E0867c52b5A50ff97579740E |
