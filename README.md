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
> 将启动节点后生成的前三个账户 导入到matemask钱包，并分别重命名为seller, firstBuyer, secondBuyer
- npx hardhat compile ## 编译智能合约
- npx hardhat run scripts/deploy.js --network localhost ## 在本地部署合约

> 用智能合约Escrow的部署地址替换 App.js 中的 escrowAddress 值

 - yarn start ## 启动前端界面
