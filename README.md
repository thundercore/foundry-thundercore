# Foundry Project Template for ThunderCore

* This is the Foundry project template configured for the ThunderCore blockchain

After creating an account named `deployer` via `cast wallet new`, try:

```
$ forge script --rpc-url thunder-testnet --broadcast --account deployer ./script/Counter.s.sol
```

Reading from the contract:

```
$ cast call --rpc-url thunder-testnet <YOUR_CONTRACT_ADDR> 'number()'

```

Writing to the contract:

```
$ cast send --rpc-url thunder-testnet --account deployer <YOUR_CONTRACT_ADDR> 'increment()'

```
