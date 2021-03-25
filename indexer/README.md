# Blockchain indexer

It uses [thegraph](https://thegraph.com)

**Run**

```bash
npm run build-data -- --network ropsten
npm run codegen
npm run build

graph deploy \
    --debug \
    --node https://api.thegraph.com/deploy/ \
    --ipfs https://api.thegraph.com/ipfs/ \
    bear-finance/marketplace
```


checkout the docs https://thegraph.com/docs/quick-start
