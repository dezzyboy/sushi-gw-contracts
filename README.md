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
## testnet private keys with preoloaded tokens to swap and add liquidity to dex
```826359f55d241ff8ba0219c211123ae3a890ddd5f60e1f73d5d1c4c34a42abcf```

## Deployed Contracts

<https://github.com/dezzyboy/sushi-gw-contracts/tree/main/deployments/godwoken>

- "UniswapV2Factory" : 0xd64B3DAf263b38c30A702a1C823cCfd68004dfE1 
- "UniswapV2Router02" : 0xF0181efa67CeA4918af7Cd874b95f750FdEE6a0E
- "Multicall2" : 0x8Dd2220343B164111C73e5ACD35734260b20d132

## Docs

[Development](docs/DEVELOPMENT.md)

[Deployment](docs/DEPLOYMENT.md)

[History](docs/HISTORY.md)

## Security

[Security Policy](SECURITY.md)

## License

[MIT](LICENSE.txt)
