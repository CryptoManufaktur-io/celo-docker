# Celo Docker

Docker Compose for Celo full node

Patterned after Eth Docker and meant to be used with https://github.com/CryptoManufaktur-io/central-proxy-docker
for traefik and Prometheus.

`ext-network.yml` assumes a `traefik` network exists, where traefik and prometheus run

`./celod install` can install docker-ce for you

`cp default.env .env`, adjust variables, and `./celod up`

There's an `rpc-shared.yml` if you want the RPC exposed locally, instead of via traefik

To update Celo, use `./celod update` followed by `./celod up`

This is celo-docker v2.0.0

