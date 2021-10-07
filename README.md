## run project

### required

- matemask
- node
- react
- hardhat
- Ethereum

### start project

- yarn install ## 安装依赖
- npx hardhat node ## 启动本地节点
- npx hardhat compile ## 编译智能合约
- npx hardhat run scripts/deploy.js --network localhost ## 在本地部署合约

用智能合约Escrow的部署地址替换 App.js 中的 escrowAddress 值
