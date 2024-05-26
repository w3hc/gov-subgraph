# Gov Subgraph

A subgraph for Gov

Integration live at **[https://gov-ui.netlify.app/](https://gov-ui.netlify.app/)**

See also:

- **[Gov Solidity contracts](https://github.com/w3hc/gov)**
- [Gov UI](https://gov-ui.netlify.app/)
- [Documentation](https://w3hc.github.io/gov-docs/)
- [Gov Deployer](https://github.com/w3hc/gov-deployer)
- [Example DAO on Tally](https://www.tally.xyz/gov/web3-hackers-collective)

## Generate subgraph

### Command line

```
graph init --studio \
  --from-contract 0xd795012382Ae5DFB52c41B34F296319b233e20C0 \
  --network sepolia \
  gov-subgraph
```

### Output

```
✔ Protocol · ethereum
✔ Subgraph name · gov-subgraph
✔ Directory to create the subgraph in · gov-subgraph
✔ Contract address · 0xd795012382Ae5DFB52c41B34F296319b233e20C0
✔ Start Block · 5975923
✔ Contract Name · Gov
✔ Index contract events as entities (Y/n) · true
  Generate subgraph
  Write subgraph to directory
✔ Create subgraph scaffold
✔ Initialize networks config
```

## Install deps

### Command line

```
yarn install
```

## Authenticate on TheGraph Studio

### Command line

```
yarn auth
```

## Generate AssemblyScript types

### Command line

```
yarn codegen
```

## Build AssemblyScript mappings

### Command line

```
yarn build
```

## Deploy on TheGraph Studio

### Command line

```
yarn deploy
```

## Support

You can contact me via [Element](https://matrix.to/#/@julienbrg:matrix.org), [Farcaster](https://warpcast.com/julien-), [Telegram](https://t.me/julienbrg), [Twitter](https://twitter.com/julienbrg), [Discord](https://discordapp.com/users/julienbrg), or [LinkedIn](https://www.linkedin.com/in/julienberanger/).

