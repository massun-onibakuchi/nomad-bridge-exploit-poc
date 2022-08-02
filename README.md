# Nomad-bridge Exploit PoC

This is just a simple poc of the attack. built for educational purposes.

## Requirements

- [Foundry](https://book.getfoundry.sh/)

## Run

Set enviroment variables.

```
export RPC_URL=<Your RRC URL>
```

Then type:

```
forge test -vvv --fork-url=$RPC_URL --fork-block-number=15259594
```

## Disclaimer

![Disclaimer](./picture.png)
