### Projeto criado no Bootcamp de NFTs pela comunidade Web3Dev, se você tem interesse em aprender a desenvolver para o mercado Web3 entre no discord da comunidade, interaja e participe dos eventos. 😎👨‍💻👩‍💻

Para iniciar o projeto utilize:
```shell
npm install
```
Depois utilize os comandos do hardhat para compilar e implantar o smart-contract:
```shell
npx hardhat compile
```
Ou apenas faça o deploy na rede, não esqueça de confiurar suas chaves privadas em `.env`:
```shell
npx hardhat run scripts/run.js --network rinkeby
```
Para verificar o contrato utilize o comando:
```shell
npx hardhat verify <contract-address>  --network rinkeby
```
Para visualizar o contrato verificado, acesse:
`https://rinkeby.etherscan.io/address/<contract-address>#code
`

## Tecnologias Usadas

- Hardhat
- Ethers
- @openzeppelin
- dotenv
- chai
- @nomiclabs/hardhat-ethers
- @nomiclabs/hardhat-etherscan
- @nomiclabs/hardhat-waffle


#### Link para o Discord: https://discord.web3dev.com.br
