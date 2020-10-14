# Curio Stablecoin System Security Audit

Security audit of Curio Stablecoin protocol contracts. This repository contains links to related Curio Stablecoin System codebase repositories (these are also included as submodules under ```scope``` folder).

## Related repositories

### Smart contracts

* [dss](https://github.com/CurioTeam/dss) - The core smart contracts code for Multi Collateral Curio Stablecoin System. This is a high level description of the system, assuming familiarity with the basic economic mechanics.
* [dss-deploy](https://github.com/CurioTeam/dss-deploy) - A smart contract which deploys the core Curio Stablecoin System contracts and sets up the necessary authorisations between them.
* [dss-cdp-manager](https://github.com/CurioTeam/dss-cdp-manager) - The manager works by having a dss wrapper that allows users to interact with their CDPs in an easy way, treating them as non-fungible tokens.
* [dss-deploy-pause-proxy-actions](https://github.com/CurioTeam/dss-deploy-pause-proxy-actions)
* [dss-proxy-actions](https://github.com/CurioTeam/dss-proxy-actions) - Set of proxy functions for Curio Stablecoin system. These functions are based on ```dss-cdp-manager``` as CDP registry.
* [dsr-manager](https://github.com/CurioTeam/dsr-manager)
* [flipper-mom](https://github.com/CurioTeam/flipper-mom) - Mom to allow protecting Flipper from kicks in real time.
* [ilk-registry](https://github.com/CurioTeam/ilk-registry) - A publicly-modifiable registry of collaterals assets in Curio Stablecoin system.
* [osm-mom](https://github.com/CurioTeam/osm-mom) - Governance interface for the OSM.
* [osm](https://github.com/CurioTeam/osm) - Oracle Security Module creates price feed with delay.
* [oracle-source](https://github.com/CurioTeam/oracle-source) - Serves as an interleave between an oracle and OSM contract.
* [median](https://github.com/CurioTeam/median) -  For a specific Ilk, the Medianizer returns the median value of several price feeds.
* [proxy-registry](https://github.com/CurioTeam/proxy-registry) - This Registry deploys new proxy instances through DSProxyFactory and keeps a registry of owner => proxy.
* [ds-chief](https://github.com/CurioTeam/ds-chief) - approval voting to select who wears the Hat by consensus.
* [ds-pause](https://github.com/CurioTeam/ds-pause) - allows authorized users to schedule function calls that can only be executed once some predetermined waiting period has elapsed.
* [ds-token](https://github.com/CurioTeam/ds-token) - Provides a standard ERC20 token interface plus [DSAuth](https://dapp.tools/dappsys/ds-auth) -protected ```mint``` and ```burn``` functions; binary approval via ```MAX_UINT```; as well as ```push```, ```pull``` and ```move``` aliases for ```transferFrom``` operations.
* [mkr-authority](https://github.com/CurioTeam/mkr-authority) - Custom authority contract for allowing Curio Governance to govern CGT token contract.
* [vote-proxy](https://github.com/CurioTeam/vote-proxy) - ds-chief CGT proxy voting with a hot/cold wallet.
* [esm](https://github.com/CurioTeam/esm) - Module for emergency stop of Curio Stablecoin System.
* [token-faucet](https://github.com/CurioTeam/token-faucet) - Mostly well behaved ERC20s faucet.
* [testchain-medians](https://github.com/CurioTeam/testchain-medians) - Due to the Medianizer having a static ```wat``` we need to have a custom contract for each one.
* [multicall](https://github.com/CurioTeam/multicall) - Aggregate multiple constant function call results into one.
* [symbolic-voting](https://github.com/CurioTeam/symbolic-voting) - Additional voting contract for Curio Stablecoin community polling engine.

### Deployment tools
* [dss-deploy-scripts](https://github.com/CurioTeam/dss-deploy-scripts) - A set of scripts that deploy Curio Stablecoin System to an Ethereum chain of your choosing.


