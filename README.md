# Ripple Regtest Docker Image

[![](https://images.microbadger.com/badges/version/ulamlabs/ripple-regtest.svg)](https://hub.docker.com/repository/docker/ulamlabs/ripple-regtest)

Docker image which bootstraps a rippled node in [stand-alone mode](https://xrpl.org/start-a-new-genesis-ledger-in-stand-alone-mode.html).

## Usage

Image is available on Docker Hub.

```
docker run ulamlabs/ripple-regtest
```

## Ports

By default, image exposes services on these ports:

- 5004 - admin RPC,
- 5005 - public RPC,
- 5006 - websocket
