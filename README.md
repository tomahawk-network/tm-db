# Tendermint DB 

[![version](https://img.shields.io/github/tag/tendermint/tm-db.svg)](https://github.com/tendermint/tm-db/releases/latest)
[![license](https://img.shields.io/github/license/tendermint/tm-db.svg)](https://github.com/tendermint/tm-db/blob/master/LICENSE)
[![API Reference](https://camo.githubusercontent.com/915b7be44ada53c290eb157634330494ebe3e30a/68747470733a2f2f676f646f632e6f72672f6769746875622e636f6d2f676f6c616e672f6764646f3f7374617475732e737667)](https://pkg.go.dev/github.com/tendermint/tm-db)
[![codecov](https://codecov.io/gh/tendermint/tm-db/branch/master/graph/badge.svg)](https://codecov.io/gh/tendermint/tm-db)
![Lint](https://github.com/tendermint/tm-db/workflows/Lint/badge.svg?branch=master)
![Test](https://github.com/tendermint/tm-db/workflows/Test/badge.svg?branch=master)
[![Discord chat](https://img.shields.io/discord/669268347736686612.svg)](https://discord.gg/AzefAFd)

Common database interface for various database backends. Primarily meant for applications built on [Tendermint](https://github.com/tendermint/tendermint), such as the [Cosmos SDK](https://github.com/cosmos/cosmos-sdk), but can be used independently of these as well.

### Minimum Go Version

Go 1.13+

## Supported Database Backends

- Arweave