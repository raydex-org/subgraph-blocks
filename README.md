# Subgraph for PulseChain block data

This subgraph indexes all block data on the [PulseChain test network]

Every block is handled by one mapping `handleBlock`

##### Note

The contract `ConverterRegistryContract` found in ABIs and subgraph.yaml is just a dummy contract used to pass formatting checks. Each block is handled automatically regardless of the logic in this contract.

### Setup

```
# Install dependencies (yarn or npm)
$ yarn or npm install

# Generate types constants
$ yarn or npm run codegen

# build subgraph
$ yarn or npm run build

# create local subgraph
$ yarn or npm run create-local

# deploy local subgraph
$ yarn or npm run deploy-local
```
