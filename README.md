# Polkadot

Polkadot is a multi-chain blockchain network that enables interoperability between specialized blockchains called parachains. It is built on the Substrate framework and maintained by the Web3 Foundation and Parity Technologies.

## APIs

This repository catalogs the public REST APIs available for querying Polkadot network data:

### Subscan API

[Subscan](https://subscan.io/) is a multi-chain block explorer for the Substrate ecosystem that provides a hosted HTTP API exposing indexed on-chain data for more than 90 networks including Polkadot and Kusama.

- **Base URL**: `https://polkadot.api.subscan.io`
- **Documentation**: https://support.subscan.io/
- **Authentication**: API key required — register at https://pro.subscan.io/
- **Rate Limits**: Free plan provides 5 req/sec and 100,000 req/day

Key endpoint categories:
- Blocks — query block details by number or hash
- Extrinsics — list and search extrinsics (transactions)
- Events — query on-chain events
- Accounts — balance info, token holdings, staking history
- Staking — validator and nominator data
- Parachain — parachain state and cross-chain data

### Substrate API Sidecar

[Substrate API Sidecar](https://github.com/paritytech/substrate-api-sidecar) is an open-source REST service maintained by Parity Technologies that provides RESTful access to Polkadot SDK-based blockchain data.

- **Public Polkadot endpoint**: `https://polkadot-public-sidecar.parity-chains.parity.io`
- **Public Kusama endpoint**: `https://kusama-public-sidecar.parity-chains.parity.io`
- **Documentation**: https://docs.polkadot.com/chain-interactions/query-data/query-rest/
- **Authentication**: None required for public instances
- **Source**: https://github.com/paritytech/substrate-api-sidecar

### Polkadot REST API

The [Polkadot REST API](https://github.com/paritytech/polkadot-rest-api) is a Rust-based rewrite of Sidecar maintained by Parity Technologies, targeting production deployments. It provides OpenAPI specifications for all endpoints.

- **Source**: https://github.com/paritytech/polkadot-rest-api
- **Authentication**: None for self-hosted instances

## Resources

- **Developer Docs**: https://docs.polkadot.com/
- **Website**: https://polkadot.com/
- **GitHub (Parity)**: https://github.com/paritytech
- **Status**: https://subscan.statuspage.io/
