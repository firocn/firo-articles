# Roadmap

## 2017

### MTP (梅克尔树工作证明)

We believe MTP is a way to prevent botnets from mining while allowing normal legitimate CPUs to perform proof of work. It allows a memory hard proof of work to be used while remaining very lightweight and quick for nodes and miners to verify. We are on track to be the first cryptocurrency to implement MTP.

### Znodes: 为处理 Zerocoin 的激励节点群

Zerocoin anonymous transactions are computationally intensive and hosting high performance nodes cost money. In order to scale Zerocoin transactions and maintain a healthy node network, it is important to have an incentivized node layer to process Zerocoin transactions and provides a secondary layer to build on services (such as a distributed marketplace).

### Sigma 协议（无信任配置）

One of the drawbacks of current zero-knowledge proof systems which offer the best anonymity currently is that it requires a trusted setup in that you need to trust people to destroy some initial generated parameters. If the parameters are somehow not destroyed, Zerocoins can be counterfeited. The Sigma protocol not only removes the need for trusted setup but also reduces Zerocoin proof sizes from 25 kb to about 1 kb allowing much greater scalability and security.

#### Bitcoin Core 升级到 0.13

We will upgrade Bitcoin Core to 0.13 first to enjoy the many improvements that the newer Bitcoin base has and simplifies integration with other Bitcoin services.

#### Zerocoin 支出给第三方

Zerocoin-spends currently can only be sent to an address you own. We can allow Zerocoin-spends directly to third party addresses.

#### 集成 Tor/I2P integration 为更强的匿名性

TOR/I2P integration will hide your wallet or nodes true IP further protecting your identity when doing transactions.

#### 隐身地址 / 支付码

Stealth addresses or payment codes allow you to give out a permanent special Zcoin address in which you cannot trace the history of that address. This is useful in giving out a address for payment without revealing how much you are receiving or paying out.

## 2018

### Sigma 协议

Development of Sigma protocol might spill over to 2018 as we further optimize it.

### 去中心化市场

To create a decentralized marketplace where users can trade items or even Zcoin without being reliant on centralized marketplaces or exchanges.

#### 多样化的钱包

Explore porting over Parity Bitcoin alternate wallet implementation for Zcoin

#### 节点之前的加密通信

Currently, communications between nodes in most cryptocurrencies are sent in the clear. Encrypted communication will make it harder to analyze transactions on the Zcoin network.

#### 开始零币可扩展性研究

To evaluate blockchain scalability solutions such as Lightning Network, Moonbeam, Extension blocks and Bitcoin Unlimited.

#### 以太坊端口和跨账本连接

Implement Zerocoin spending verifications on smart contracts with the goal of creating a decentralized (and in the future trustless) coin mixer for Ether. Will only be possible once Metropolis is released.

## 2019

### 实现区块链可扩展性方案

### 基于 Zerocoin 技术的去中心化匿名投票系统

### Blind auction system

### Zcoin 实验室

### Zcoin 基金会

#### 免责声明：

The roadmap information above is being shared in order to outline some of our current plans and best estimates for Zcoin, but like everything else in life, things can change even the best laid plans. We are hopeful that the following can shed some light on our roadmap, but it is important to understand that it is being shared for INFORMATIONAL PURPOSES ONLY, and not as a binding commitment. Please do not rely on this information in making purchasing decisions because ultimately, the development, release, and timing of any features or functionality remains at the sole discretion of the Zcoin team, and is subject to change.
