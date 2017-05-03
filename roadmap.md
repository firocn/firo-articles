# 路线图

## 2017

### MTP（梅克尔树工作量证明）

We believe MTP is a way to prevent botnets from mining while allowing normal legitimate CPUs to perform proof of work. It allows a memory hard proof of work to be used while remaining very lightweight and quick for nodes and miners to verify. We are on track to be the first cryptocurrency to implement MTP.

我们认为 MTP 是阻止僵尸网络挖矿的一种方法，同时允许正常的合法 CPU 执行工作证明。它允许使用高内存要求的工作证明，同时保持非常轻量快速的节点和矿工验证。我们正在成为实施 MTP 的第一个加密货币。

### Znodes：为处理 Zerocoin 的激励节点群

Zerocoin anonymous transactions are computationally intensive and hosting high performance nodes cost money. In order to scale Zerocoin transactions and maintain a healthy node network, it is important to have an incentivized node layer to process Zerocoin transactions and provides a secondary layer to build on services (such as a distributed marketplace).

Zerocoin 匿名交易是计算密集型的，并且托管高性能节点需要花钱。为了扩展 Zerocoin 交易并维护一个健康的节点网络，有一个激励节点层来处理 Zerocoin 交易并提供一个二级层来建立服务（如分布式市场）是非常重要的。

### Sigma 协议（无信任配置）

One of the drawbacks of current zero-knowledge proof systems which offer the best anonymity currently is that it requires a trusted setup in that you need to trust people to destroy some initial generated parameters. If the parameters are somehow not destroyed, Zerocoins can be counterfeited. The Sigma protocol not only removes the need for trusted setup but also reduces Zerocoin proof sizes from 25 kb to about 1 kb allowing much greater scalability and security.

目前提供最佳匿名性的零知识证明系统的缺点之一是它需要一个可信任的配置，你需要信任人们销毁一些初始生成的参数。如果参数以某种方式未被销毁，则可以伪造 Zerocoin。Sigma 协议不仅消除了对可信配置的需求，而且还将 Zerocoin 证明大小从 25 kb 降低到约 1 kb，从而实现了更大的可扩展性和安全性。

#### Bitcoin Core 升级到 0.13

We will upgrade Bitcoin Core to 0.13 first to enjoy the many improvements that the newer Bitcoin base has and simplifies integration with other Bitcoin services.

我们会先将 Bitcoin Core 升级到 0.13，以享受较新的 Bitcoin Core 的许多改进，并简化与其他 Bitcoin 服务的集成。

#### Zerocoin 支出给第三方

Zerocoin-spends currently can only be sent to an address you own. We can allow Zerocoin-spends directly to third party addresses.

Zerocoin 目前只能发送到你自己的地址。我们可以直接让 Zerocoin 发送到第三方地址。

#### 集成 Tor/I2P 为更强的匿名性

TOR/I2P integration will hide your wallet or nodes true IP further protecting your identity when doing transactions.

TOR/I2P 集成将隐藏你的钱包或节点的真实 IP，在进行交易时进一步保护你的身份。

#### 隐身地址/支付码

Stealth addresses or payment codes allow you to give out a permanent special Zcoin address in which you cannot trace the history of that address. This is useful in giving out a address for payment without revealing how much you are receiving or paying out.

隐身地址或支付码允许你放出永久的特殊零币地址，你无法追踪该地址的历史记录。这对放出一个收款地址而不透露收到或支付多少有用。

## 2018

### Sigma 协议

Development of Sigma protocol might spill over to 2018 as we further optimize it.

随着我们进一步优化，Sigma 协议的开发可能会延伸到 2018 年。

### 去中心化市场

To create a decentralized marketplace where users can trade items or even Zcoin without being reliant on centralized marketplaces or exchanges.

创建一个去中心化的市场，用户可以在不依赖中心化市场或交易所的情况下交易物品甚至零币。

#### 备选钱包

Explore porting over Parity Bitcoin alternate wallet implementation for Zcoin

为零币探索移植同等的 Bitcoin 备选钱包实现。

#### 节点之前的加密通信

Currently, communications between nodes in most cryptocurrencies are sent in the clear. Encrypted communication will make it harder to analyze transactions on the Zcoin network.

目前，大多数加密货币中的节点之间的通信是以明文方式发送的。加密的通信将会让分析零币网络上的交易变得更加困难。

#### 开始零币可扩展性研究

To evaluate blockchain scalability solutions such as Lightning Network, Moonbeam, Extension blocks and Bitcoin Unlimited.

评估闪电网络、Moonbeam、延展区块和 Bitcoin Unlimited 等区块链可扩展性方案。

#### 以太坊端口和跨账本连接

Implement Zerocoin spending verifications on smart contracts with the goal of creating a decentralized (and in the future trustless) coin mixer for Ether. Will only be possible once Metropolis is released.

在智能合约上实现 Zerocoin 支出交易验证，目的是为以太币创建一个去中心化的（并且在未来无信任）混币器。Metropolis 发布后才有可能。

## 2019

### 实现区块链可扩展性方案

### 基于 Zerocoin 技术的去中心化匿名投票系统

### 第一价格密封拍卖系统

### 零币实验室

### 零币基金会

#### 免责声明：

The roadmap information above is being shared in order to outline some of our current plans and best estimates for Zcoin, but like everything else in life, things can change even the best laid plans. We are hopeful that the following can shed some light on our roadmap, but it is important to understand that it is being shared for INFORMATIONAL PURPOSES ONLY, and not as a binding commitment. Please do not rely on this information in making purchasing decisions because ultimately, the development, release, and timing of any features or functionality remains at the sole discretion of the Zcoin team, and is subject to change.

上述路线图信息处于分享中，以概述我们目前的计划和零币的最佳预期，但像生活中的其他一切事情，事情可以改变，即使是最好的计划。我们希望大家能够大致了解我们的路线图，但重要的是要明白，它只是为了分享信息，而不是承诺。请不要依赖这些信息做出购买决定，因为最终，开发、发布和任何功能的实现，仍然由零币团队自行决定，并且可能会改变。
