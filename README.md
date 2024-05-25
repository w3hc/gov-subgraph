# gov-subgraph

## Generate subgraph

### Command line

```
graph init \
  --from-contract 0xd795012382Ae5DFB52c41B34F296319b233e20C0 \
  --network sepolia \
  --abi Gov.json \
  w3hc/gov-subgraph gov-subgraph
```

### Output

```
✔ Protocol · ethereum
✔ Product for which to initialize · hosted-service
✔ Subgraph name · w3hc/gov-subgraph
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

## Generate AssemblyScript types

### Command line

```
yarn codegen
```

## Generate AssemblyScript types

### Command line

```
yarn build
```
