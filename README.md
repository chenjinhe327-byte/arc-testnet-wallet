# HelloArcToken ARC Testnet DApp Wallet
基于 Arc Testnet 开发的 ERC-20 代币演示网站与可视化网页钱包，纯前端静态部署，可连接 MetaMask 完成链上余额查询、代币转账。

## 项目介绍
- 代币名称：HelloArcToken
- 代币符号：ARC
- 小数位数：18
- 总发行量：21,000,000 ARC
- 合约状态：永久关闭铸币权限，总量固定，去中心化不可增发
- 合约地址：`0x5916804cfd7db5ce08861732969f1861304d216a`
- 适用网络：Arc Testnet（仅测试网，无真实资产价值）

## 在线访问地址
1. 项目官网首页
https://6a1c727f9a3b3f3efe5bfc09--illustrious-babka-805c4c.netlify.app/

2. MetaMask 可视化钱包（转账功能）
https://6a1c727f9a3b3f3efe5bfc09--illustrious-babka-805c4c.netlify.app/wallet.html

## 功能说明
### 官网首页 index.html
- 展示代币基础信息、合约地址、安全特性
- 一键跳转区块浏览器查看合约
- 直达可视化钱包入口
- 顶部风险提示，标注仅测试网演示

### 网页钱包 wallet.html
- 连接 MetaMask 浏览器钱包
- 自动读取当前钱包 ARC 代币余额
- 支持填写接收地址、转账数量，发起链上交易
- 交易成功弹窗返回区块哈希，可在 ArcScan 查看交易记录

## 技术栈
- 纯静态前端：HTML + CSS + JavaScript
- 链上交互依赖 Ethers.js v6 CDN
- 托管平台：Netlify（自动 HTTPS、全球CDN）
- 区块链：Arc EVM Testnet

## 重要风险声明
⚠️ 本项目仅用于 Arc 测试网技术演示，所有代币为测试资产，无任何实际价值。
请勿存入 USDC、ETH 等真实资金，项目不承担任何资产损失风险。

## 本地运行方式
1. 下载仓库全部文件到本地
2. 直接双击 `index.html` 在浏览器打开
3. 钱包页面依赖 MetaMask 插件，无插件无法连接链上

## 区块浏览器
Arc Testnet Scan：https://testnet.arcscan.app/
