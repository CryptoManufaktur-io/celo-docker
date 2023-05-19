# celo-docker

docker compose for Celo full node

Patterned after eth-docker and meant to be used with https://github.com/CryptoManufaktur-io/base-docker-environment
for traefik and Prometheus.

`ext-network.yml` assumes a `traefik` network exists, where traefik and prometheus run

`.ethd install` can install docker-ce for you

`cp default.env .env`, adjust variables, and `./ethd up`

There's an `rpc-shared.yml` if you want the RPC exposed locally, instead of via traefik

To update Celo, use `./ethd update` followed by `./ethd up`

This is celo-docker v1.0

