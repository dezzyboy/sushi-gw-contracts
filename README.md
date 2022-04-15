# SushiSwap ported to godwoken

## Getting started

```
git clone https://github.com/dezzyboy/sushi-gw-contracts.git
```

```
 cd sushi-gw-contracts
```

```
cp .env.example .env
```

## Deploy contract

```
yarn && yarn build
```

```
yarn godwoken:deploy
```

## Deployed Contracts

<https://github.com/dezzyboy/sushi-gw-contracts/tree/main/deployments/godwoken>

- "UniswapV2Factory" (tx: 0x133d5dd3782561d0275d8668cfbcb02a15fc9c5dc53612dd37e3c822e922dd93)...: deployed at 0xd64B3DAf263b38c30A702a1C823cCfd68004dfE1 with 23346 gas
- "UniswapV2Router02" (tx: 0x2183fefa9feab9d293ee0dcb2da5cc10edc7348226cd4171d52a80aa7571684a)...: deployed at 0xF0181efa67CeA4918af7Cd874b95f750FdEE6a0E with 4657 gas

## Docs

[Development](docs/DEVELOPMENT.md)

[Deployment](docs/DEPLOYMENT.md)

[History](docs/HISTORY.md)

## Security

[Security Policy](SECURITY.md)

## License

[MIT](LICENSE.txt)
