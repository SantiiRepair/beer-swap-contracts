## Beer Swap Contracts 🍺

This repo contains all the contracts used in  Beer Swap. It is divided in independent projects where each of them contains its smart contracts, test environment and unique config files.

### Existing projects

| Project name                                                          | Description                                                                                                                | Solidity version(s)      |
| --------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------- | ------------------------ |
| [BRT Token](./contracts/projects/brt-token)                                     | Created with @openzepellin library, it combines BEP20 interface and transfers to be used.                                  | 0.5.16 / 0.6.6 / 0.8.4   |
| [BRT Stake](./contracts/projects/brt-stake/Stake.sol)                           | BRT Stake ("Pools") contract that allows auto-percentage montly for BRT tokens.                                            | 0.8.1.                   |


### Create a new project

1 - Create a new folder inside `projects` <br/>
2 - Run `yarn init`

Commands inside the root `package.json` starting with `lerna` will run the corresponding command in each subproject.
