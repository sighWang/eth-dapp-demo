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

## ethereum dapp开发学习

### 参考

以太坊智能合约开发语言 [solidity][https://docs.soliditylang.org/en/v0.8.7/]

以太坊dapp开发环境[hardhat][https://hardhat.org/]

以太坊前端库 [Ethers.js][https://docs.ethers.io/v5/]

前端UI框架 React

以太坊Dapp [开发框架列表](https://ethereum.org/en/developers/docs/frameworks/#top)

[Infura](https://infura.io/)， [Alchemy](https://www.alchemyapi.io/) 为开发人员提供了一种不必运行全节点就可以连接以太坊网络的方法。

[了解比特币和以太坊](https://www.bilibili.com/video/BV1Vt411X7JF?p=1) bilibili北大肖臻视频课

如何构建一个完整的全栈的以太坊dapp开发（React， Solidity，Hardhat，Ethers.js,Matemask, infura）https://dev.to/dabit3/the-complete-guide-to-full-stack-ethereum-development-3j13

如何构建一个逻辑更加复杂的dapp https://dev.to/steadylearner/how-to-make-a-fullstack-dapp-with-react-hardhat-and-ether-js-with-examples-4fi2



提供一个全栈的在CKB上开发dapp的教程，包括项目搭建，启动本地节点，部署本地节点，部署测试网，部署主网。提供最佳实践等。
