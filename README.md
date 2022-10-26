# Base Fee Provider

On supported networks, this contract reads block.basefee and reports it for interpretation by the [base fee oracle](https://github.com/yearn/yearn-vaults/blob/master/contracts/BaseFeeOracle.sol). The latest version of this contract is also found in this repo as well.

BaseStrategy versions prior to 0.4.5 hardcode an earlier version of the base fee oracle (legacy) that also has a hardcoded base fee provider address.

## Current Deployments (v0.1.0)

| Chain    | Contract | Deployment Address |
| -------- | -------- | ------------------ |
| Ethereum | Provider | Text               |
| Ethereum | Oracle   | Text               |
| Fantom   | Provider | Text               |
| Fantom   | Oracle   | Text               |
| Arbitrum | Provider | Text               |
| Arbitrum | Oracle   | Text               |
| Optimism | Provider | Text               |
| Optimism | Oracle   | Text               |

## Legacy Deployments

| Chain    | Contract | Deployment Address                         |
| -------- | -------- | ------------------------------------------ |
| Ethereum | Provider | 0xf8d0Ec04e94296773cE20eFbeeA82e76220cD549 |
| Ethereum | Oracle   | 0xb5e1CAcB567d98faaDB60a1fD4820720141f064F |
| Arbitrum | Provider | 0xFf72f7C5f64ec2fd79B57d1A69C3311C1bB3EEF1 |
| Arbitrum | Oracle   | 0xdF43263DFec19117f2Fe79d1D9842a10c7495CcD |
| Optimism | Provider | 0x46679Ba8ce6473a9E0867c52b5A50ff97579740E |
