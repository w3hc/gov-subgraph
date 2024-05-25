# gov-subgraph

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
