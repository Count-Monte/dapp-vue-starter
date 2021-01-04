# dapp-vue-starter

## Project setup

```
npm install
```

### Compile contracts

```
npm run compile
```

### Migrate contracts

```
npm run migrate
npm run migrate --network mycustomnetwork
npm run migrate:reset
```

### Run truffle tests

```
npm run test
```

### Run truffle console

```
npm run console
```

### Run Solidity linter (solhint)

```
npm run solhint
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

### Run ganache-cli in docker - simplest version

```
docker run --detach --publish 8545:8545 trufflesuite/ganache-cli:latest
```

### Run ganache-cli in docker with additional parameters

```
docker run --detach --publish 8545:8545 trufflesuite/ganache-cli:latest --verbose --blockTime=5 --accounts=20
```

### Build production ready docker image

```
docker build --tag dapp-vue-starter .
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).
