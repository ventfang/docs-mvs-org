title: Metaverse 白皮书
comments: false
---

## Metaverse 核心要素

元界是中国领先的公有区块链，旨在为广大用户提供方便安全的基于区块链的基础设施，从而建立一个具备智能属性的去中心化网络。元界的三大核心要素是数字资产、数字身份和价值中介。

### 数字资产（Digital Asset）：

数字资产是指在元界中以电子数据存在的，受区块链加密技术保护的可定义、可编写的资产。用户可以在元界上自行创建和登记数字资产，并进行赠送、转让、质押、交易等一系列行为。

### 数字身份（Avatar）：

数字身份是用户所拥有的主私钥所对应的账户的Profile信息的统称。Profile拥有一个全网唯一标识，在元界中，我们称该标识为DID（Digital Identity）。数字资产的所有权可以通过个人对数字身份的掌控、再由数字身份以数学上不可伪造的方式持有。Avatar作为一个线上身份的象征，可以代表人们在区块链上持有数字资产。数字身份可以让用户不必依赖第三方机构，即可创建、签署、验证其身份并将能够轻松地处理元界上任何类型的资产。

### 价值中介（Oracle）:

Oracle作为元界的生态中的价值中介（Value Intermediary），负责验证数据来源的真实性及有效性，除了个体数字身份可以对真实性进行背书外，我们还引入了托管方、监管方和身份认证机构等第三方作为Oracle，对数据进行背书。此外 Oracle 还可以丰富交易类型，提升区块链价值。

### BaaS（Blockchain-as-a-Service）

区块链即服务是指企业或个人可以根据自己的实际需求，向区块链解决方案供应商定制区块链服务。作为中国领先的公有链开源项目，元界将会提供更多基础性的区块链服务设施，以便更多第三方开发者能够基于元界生态进行应用插件的开发，让更多普通用户能够便捷地使用我们的数字资产及数字身份的登记与管理服务。

## 代币信息

Metaverse 的原生代币为ETP，发行量为一亿个，ETP 的最小单位是0.00000001，即小数点后八位小数。它代表了 Metaverse生态体系内的一种的权益。ETP将被用来衡量 Metaverse上智能资产的价值，或者作为金融交易中的一般担保物。ETP还可用来支付元界上的费用，例如创建智能资产，注册Avatar，将自己标记成为一名 Oracle，或者在Metaverse上请专业机构对以上的资产或身份进行认证。

Metaverse项目的ETP已经通过一次ICO，向外界分发了2500万个ETP，还有2500万个ETP用于设立元界基金会，来支持对元界社区有促进作用的区块链项目ICO，进行有利于元界生态的投资活动，以及对社区主要贡献者进行奖励。3000万的ETP将以区块奖励的方式分发给系统的维护者。

考虑到ETP在流通过程中有部分丢失，零头损耗，以及大量质押和交易所囤积情况的可能，我们设计的ETP经济模型需要引入微通胀来弥补ETP流通的需求。在 ETP 的经济模型设计中，我们加入了系统级别的有偿锁币功能，这对区块链的经济系统来说是新的设计，其设计理念可以概述为——将币龄概念代币化，为未来PoS共识的经济模型、以及由锁币衍生的金融应用做长远的铺垫。用户需要主动去使用锁币功能，才能获得系统的ETP奖励。这个奖励在锁币操作完成的瞬间将通过一种新的coinbase交易类型打入用户的锁币地址。在锁币奖励过程中，我们将持续、有序地向系统释放少量的ETP奖励，具体的量将由锁币的总量、时限来决定，同时通胀率又会作为参数，反馈给ETP锁币奖励利率的调整。

## 共识机制

### 基本信息

区块链共识过程是指将全网交易数据客观记录并且不可篡改的过程。共识过程主要以共识算法实践体现，目前元界的共识机制有两个，具体如下：

**第一阶段：PoW 机制**

在元界系统的前几年运行时间中，将会采用GPU挖矿的方式，以及一个去中心化的时间戳服务来保障系统安全。元界的挖矿算法还在比较和研究中，我们会避免使用比特币的SHA256算法和莱特币的scrypt算法，原因是避免比特币或莱特币矿池51%算力攻击。目前我们计划采用ETHASH算法。

**第二阶段：HBTH-DPoS**

虽然PoW工作量证明机制的挖矿可以帮助元界系统在最初的几年内有系统安全的保障，但是PoW挖矿也有它的问题，比如说能源的浪费，挖矿的中心化发展趋势等等。

大多数的加密货币都选择性忽略拜占庭容错算法，因为这个算法不解决代币分发的问题。元界的ETP虽然不是货币，但是作为对网络安全有贡献节点的回馈，ETP将被分发给这些节点。

在任何区块链项目的早期，全节点的总量都是不足的，这样全网的系统安全就比较难有保障。通过引入工作量证明挖矿的机制，元界向挖矿节点分发ETP作为区块奖励，系统本身会获得大量矿工全节点，可以在项目早期提供足够的系统安全性。

未来随着项目越来越成熟，用于进行挖矿奖励的ETP分发会接近尾声，元界将切换到一种改良的DPoS共识算法上，这种算法将考虑“币区块高度销毁”这个重要指标设计。

元界改进了DPoS共识机制，加入了币区块高度和心跳的概念，基本的模型如下：

币区块高度（TH）源于币天销毁的概念；
比特币的币天=比特币数量×上一次花费至今的天数；
TH=ETP的数量×上一次花费至今的区块数×元界常数。

元界将TH作为DPoS中投票的权重，目的是避免金融干扰问题，如果攻击者临时从市场获得大量的ETP打算对投票进行影响，那么他们的币区块高度将很小，因此投票的影响力也很弱。攻击者为了达到目的，将不得不从市场上获得更多的ETP，或者持有ETP达到足够长的时间来获取币区块高度，不论是哪一种方式都将显著增加攻击者的成本。

在DPoS阶段，元界与其他采用PoS共识机制的系统一样，会根据当时的权益持有情况把ETP分发给不同的ETP持有人。不过，不同之处在于，元界系统的ETP持有人将不是以被动接收代币的方式获得新的ETP，而是需要持有人向系统发送一个“心跳”以证明该ETP持有者还是活跃的。同时这个心跳相当于一个来自ETP持有人私钥的数字签名，ETP持有人在发送心跳的时候还要选择更换或维持自己的权益代表。

在DPoS阶段，我们也将考虑使用Power-DPoS改进算法。

## ETHASH算法

元界采用了以太币（ether）的挖矿算法Ethash（又名Dashimoto（Dagger-Hashimoto）） 。ETHASH的特点是挖矿的效率基本与CPU无关，却和内存大小和内存带宽正相关。ETHASH算法对内存大小和带宽的要求意味着那些通过共享内存的方式大规模部署的矿机芯片不能在挖矿效率上实现线性或者超线性（super-linear）的增长。

## 椭圆曲线数字签名算法（ECDSA）

椭圆曲线数字签名算法（Elliptic Curve Digital Signature Algorithm，缩写为ECDSA）是一种密码学算法，用来保证全部信息交流的数据记录到每一个区块中，每一个区块都会生成相应的数字签名，用于验证信息的有效性。ETP的安全性由椭圆曲线数字签名算法保障。

## 未花费交易输出（UTXO）

与以太坊的设计不同，元界的原生数字资产ETP将沿用比特币系统的UTXO (Unspent Transaction Output 未交易输出) 方法，任何交易都将由一组输入和输出定义，并且带有当前ETP的所有者和之前交易者的私钥签名，由以上这些元素共同组成新的UTXO。而智能资产将尝试账户模型，这样既不会过分增加系统的复杂度，也能保留UTXO的好处。

这样设计的结果是，元界上的数字资产将像比特币一样可以很方便地进行接收和发送，只有当更复杂的交易模式需求出现的时候，才会需要智能合约。

