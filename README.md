# dapp-vue-starter

## Project setup

```
npm install
```

### Compiles contracts

```
npm run compile
```

### Migrates contracts

```
npm run migrate
npm run migrate --network mycustomnetwork
npm run migrate:reset
```

### Runs truffle tests

```
npm run test
```

### Runs truffle console

```
npm run console
```

### Runs Solidity linter (solhint)

```
npm run solhint
```

### Runs prettier on Solidity contracts

```
npm run prettier:solidity
```

### Compiles and hot-reloads for development

```
npm run serve
```

### Compiles and minifies for production

```
npm run build
```

### Lints and fixes files

```
npm run lint
```

## Docker

### Runs ganache-cli in docker - simplest version

```
docker run --detach --publish 8545:8545 trufflesuite/ganache-cli:latest
```

### Runs ganache-cli in docker with forked mainnet

```
ganache-cli -f https://cloudflare-eth.com
```

### Runs ganache-cli in docker with forked mainnet and unlocked account

```
ganache-cli -f https://cloudflare-eth.com -u "0x41653c7d61609D856f29355E404F310Ec4142Cfb"
```

### Runs ganache-cli in docker with additional parameters

```
docker run --detach --publish 8545:8545 trufflesuite/ganache-cli:latest --verbose --blockTime=5 --accounts=20
```

### Builds production-ready Docker image (Nginx as a web server)

```
docker build --tag dapp-vue-starter .
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
