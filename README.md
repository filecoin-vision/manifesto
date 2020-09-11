# Filecoin Vision 宣言

[English version](#the-filecoin-vision-project-manifesto)

我们都知道 Filecoin，它是由协议实验室主导设计和研发的新一代去中心化存储公链，历时三载，众多人呕心沥血地参与研究、开发、测试，也背负着太多投资人、矿工、用户的期望，在接下来的几个月中将上线主网。然而 Filecoin 社区逐渐看到了一些严重的亟待解决的问题，可是这些问题几乎很难由协议实验室来轻松理解和解决。

这里列出 Filecoin 的一些令人棘手的争议点：
- 可挖矿份额从 70% 降至主网初期的 30% 左右
- 前置抵押和后置区块奖励线性释放
- Window PoSt 半小时内失败而导致代币惩罚，且必须隔天才能修复
- 验证人验证的承诺数据具有 10 倍存力
- 协议实验室倾向于用道德来约束矿工的行为，而不是链上规则
- 协议实验室拥有 15% 的代币，基金会拥有 5% 的代币

Filecoin Vision（Filecoin 愿景），简称为 **FILV** 或 **FIV**，是一个更去中心化的存储公链项目，将是完全由社区主导的 Filecoin 姊妹链，大部分源代码将 fork 自 Filecoin 上游代码仓库 lotus 及其依赖库。社区将完全决定 Filecoin Vision 的经济模型设计和参数制定、新特性/功能开发、链上治理，不会有太多条条框框，而是极力鼓励创新、竞争，尽极大可能地利用区块链思维推动去中心化存储的应用落地。

FILV 将实施众多激动人心的改进：
- 可挖矿份额提升到 99%
- 减少前置抵押额度，让每一个矿工都能轻松参与挖矿
- Window PoSt 允许宽容性地重试提交
- Garbage 扇区丢失或掉线，将不用承受对抵押币的惩罚
- 宽容性惩罚，实施惩罚一定是确定恶意行为并绝不过度惩罚
- 不能通过链上规则良好辨别出来的恶意行为，绝不实施惩罚
- 惩罚将预先确定但延期执行，避免引起多米诺骨牌反应
- 没有验证人，没有验证的承诺数据
- 提倡道德，但更倾向于合理化链上规则，不排斥人性自私

更多可改进点，等待社区参与者来提议。

## FAQ

#### Filecoin Vision 是否会像很多侧链/分叉链那样走向死亡?

坦白地说，有可能会的。
FILV 作为 Filecoin 的孪生链，尤其受到 Filecoin 主网上线前后一些变动的影响。更直接地，如果协议实验室看到并愿意吸收利用 FILV 提出的一些建议或修改，将其实施到 Filecoin，那么 FILV 将逐渐失去它存在的价值，社区将重新聚焦到浪子回头后的 Filecoin。如果真得发展到这样一个局面，FILV 将解散社区，终止代码仓库更新且不启动主网。

反过来说，也有可能不会。尤其是协议实验室继续固执己见，不听取社区的合理声音，在经济模型上继续刁难矿工，在存储生态上继续中心化路线，那么 FILV 作为更去中心化和更照顾生态参与者的替代者，终将取代并完全超越 Filecoin。

#### Filecoin Vision 将由谁来掌控或主导?

社区。任何个人或机构都没有资格或可能性来试图“掌控” FILV 网络。FILV 从现在开始到上线后一段时间之内，将由几个核心发起人来牵头协调社区讨论、经济模型参数确定、代码合并与修改、新功能设计与实现、测试网启动与维护。然而发起人并没有权利谋取超过他们贡献之外的私利。理想情况下，发起人将在 3 到 6 年之内完全更换一批。FILV 将内建链上治理的系统合约，监督、约束和激励早期发起人以及重要的生态参与者。链上治理的实施，将完全由社区通过链上投票来裁决，最终多数票的决定将胜出。完全去中心化的链上治理，是低效的，甚至走向无为/无能治理，但 FILV 秉持去中心化的理想，不应做任何妥协。

#### Filecoin Vision 的经济模型或代币分发规则将怎样确定?

完全交给社区来讨论和确定。FILV 没有项目方或主体，其最重要的经济模型或代币分发规则，当然也得交给社区来定。不过我们知道人性自私，区块链项目的良好发展，极大程度取决于发起人或其他重要贡献者的持续付出，建议给予他们一些代币激励。FILV 将设置一个激励池，比如 **1%**，能够从激励池中获得按线性释放模式激励的贡献者将包括发起人、开发者、生态建设者，甚至包括协议实验室（如果他们愿意的话；毕竟 FILV 确实公开使用了他们的很多研发成果）。那么剩下的 **99%**，将完全由矿工提供存力挖矿获得。这里所举例的百分比数值，也将由社区来最终确定。

#### Filecoin Vision 的代币 FIV 会上交易所吗?

不知道。FILV 没有主体，将完全是由社区自发参与的区块链项目，因此也不会有人主动花钱去上交易所。然而 FIV 代币的价值，是否需要交易所来体现，值得社区思考。如果交易所看到 FIV 的价值，愿意主动上币，那也与 FILV 社区没有直接关系。

#### Filecoin Vision 需要什么样的参与者?

FILV 应该需要具有以下特质的参与者：
- 开发者：实现 FILV 社区决定的规则更改、新功能增强等
- 经济学家：提出和测算改进的经济模型及其实施效果
- 矿工：贡献存力参与挖矿，构建强大稳定的去中心化存储网络
- 应用开发者或服务提供者：构建客户端应用，提供具有良好使用体验的存储或检索服务
- 媒体：宣传 FILV 的理念和愿景，追踪和发布 FILV 发展动态
- 存储用户：愿意为存储交易和检索交易付费
- 代币持有者：将 FIV 作为价值存储和交换的媒介

FILV 的发起人也将从上述参与者中发掘，人数控制在 5 到 10 人以内。

#### Filecoin Vision 早期参与者会得到哪些好处?

没有任何有**现实价值**的好处。早期参与者应该是一批关注或深入 Filecoin 多时的理想主义者，看到其不足之处，被 FILV 的愿景所吸引而自发或义务地参与到 FILV 生态建设中来。

然而，早期参与者将有更大机会获得更多 FIV 代币，即使短期来看，它一文不值。

#### Filecoin Vision 会限制大矿工吗?

不会，但会在一定程度上尽量制定链上规则来鼓励矿工分散自己的存力到不同的矿工号。FILV 不想陷入垃圾数据堆积增长的军备竞赛中，应该提倡良性竞争和减少碳排放。

# The Filecoin Vision Project Manifesto

[中文版本](#filecoin-vision-%E5%AE%A3%E8%A8%80)

We all know Filecoin, the next generation of decentralized storage blockchain designed and developed by the Protocol Labs. Three years have passed, many people have participated in its research, development and testing, with painstaking effort. It's also expected a lot by too many investors, miners, users. The mainnet will be launched in the next few months. However, the Filecoin community has gradually seen some serious problems which need to be solved, but these problems are almost difficult to be easily understood and solved by the Protocol Labs.

Here are some thorny issues of Filecoin:

- The token share for mining has dropped from 70% to about 30% in the initial stage of the mainnet
- The pre-pledge of sectors and linear release of block rewards
- Window PoSt fails within half an hour and results in token penalty, and the failure must be delayed to the next day for repair.
- The committed data verified by the validator is 10 times more powerful for mining
- Protocol Labs tends to use ethics to restrict the behavior of miners, rather than rules on the chain
- Protocol Labs owns 15% of tokens, and the Foundation owns 5% of tokens

Filecoin Vision (Filecoin Vision), abbreviated as **FILV** or **FIV**, is a more decentralized storage blockchain project, as a sister chain of Filecoin, fully led by the community. Most of the source code will be forked from the Filecoin Lotus upstream code repository and its dependent libraries. The community will completely determine Filecoin Vision’s economic model design and parameter formulation, new features/function development, and on-chain governance. There will not be too many restrictions, but will strongly encourage innovation and competition, and use the blockchain thinking to push forward the large scale application of decentralized storage as much as possible.

FILV will implement many exciting improvements:

- The token share for mining is increased to 99%
- Reduce the amount of pre-pledge, so that every miner can easily participate in mining
- Window PoSt allows tolerant retry-and-submit later on
- If garbage sectors are lost or offline, no penalty will be conducted
- Encourage tolerant punishment, and punishment can only be carried out after some malicious behavior had been deterministically distinguished out, and never punish too excessive
- Malicious behavior that cannot be distinguished out by the on-chain rules will never be punished
- Penalties will be determined in advance but be postponed for some time to avoid domino effect
- No validator, no verified commitment data
- Promote ethics, but prefer to rationalize the rules on the chain, and do not exclude human selfishness

Open for more improvement proposals from community participants.

## FAQ

#### Will Filecoin Vision die some day, like many sidechains or fork chains?

Frankly speaking, it might be. As the sister chain of Filecoin, FILV is especially affected by some changes before and after the Filecoin mainnet launch. More directly, if the Protocol Labs likes and absorbs some of the suggestions or modifications made by FILV and implement them in Filecoin, then FILV will gradually lose its value, and the community will refocus on Filecoin like a prodigal son. If it really comes in such a situation, FILV will disband the community, terminate the code repository update and not launch the mainnet.

Conversely, it may not. In particular, the Protocol Labs sticks to be stubborn, does not listen to the reasonable voice of the community, continues to make things difficult for miners in the economic model, and continues the centralized path in the storage ecology, then FILV, as an alternative which is more decentralized and cares about ecological participants, will eventually replace and completely surpass Filecoin.

#### Who will control or lead Filecoin Vision?

Community. No individual or organization has the qualification or possibility to try to "control" the FILV network. From now on to a period of time after FILV goes online, several core initiators will lead the coordination of community discussions, economic model parameter determination, code merging and development, new feature design and implementation, and testnet startup and maintenance. However, initiators have no right to seek personal gains beyond their contributions. Ideally, the initiators will completely be replaced by new guys, within 3 to 6 years. FILV will build a system contract for on-chain governance to supervise, restrict and motivate early initiators and some important ecological participants. The conduction of on-chain governance will be completely determined by the community through on-chain voting, and the final majority vote will win. Fully decentralized on-chain governance is inefficient and may even move toward inaction/incompetence governance, but FILV upholds the ideal of decentralization and should not make any compromises.

#### How will Filecoin Vision's economic model or token distribution rules be determined?

It is completely left to the community to discuss and determine. FILV has no project parties or subjects, and its most important economic model or token distribution rules must of course be left to the community to determine. However, we know that human nature is selfish, and the good development of a blockchain project depends, to a large extent, on the continuous contributions of initiators or other important contributors. We recommend giving them some token incentives. FILV will set up an incentive pool, such as **1%**. Contributors who can get incentives in a linear release model from the incentive pool will include initiators, developers, ecological builders, and even Protocol Labs (if they want; after all, FILV will indeed use many of their research and development results). Then the remaining **99%** will be mined out entirely by the miners. The percentage values ​​exemplified here will also be finalized by the community.

#### Will Filecoin Vision's token FIV be listed on the exchange?

Nobody knows. FILV has no subject and will be entirely a blockchain project spontaneously participated in by the community, so no one will actively spend money to make it listed on the exchange. However, whether the value of FIV token needs to be reflected by an exchange is worth the community's thinking. If the exchange sees the value of FIV and is willing to take the initiative to list the currency, it has no direct relationship with the FILV community.

#### What kind of participants does Filecoin Vision need?

FILV should need participants with the following characteristics:

- Developer: implement on-chain rule changes and new feature enhancements decided by the FILV community
- Economist: propose the improved economic model and measure its effect
- Miners: contribute their resources to participate in mining, build a strong and stable decentralized storage network
- Application developers or service providers: build client applications and provide storage or retrieval services with good user experience
- Media: publicize FILV's philosophy and vision, and publish FILV development news
- Storage users: willing to pay for storage transactions and retrieval transactions
- Token holders: use FIV as a medium of value storage and exchange

FILV sponsors will also be discovered from the above mentioned participants, and the number of people will be controlled within 5 to 10.

#### What benefits will early participants of Filecoin Vision get?

There is no benefit of **real value**. Early participants should be a group of idealists who have paid close attention to or understood Filecoin for a long time. Seeing its shortcomings, they were attracted by FILV's vision and spontaneously or voluntarily participated in FILV ecological construction.

However, early participants will have a greater chance of acquiring more FIV tokens, even if it is worthless in the short term.

#### Will Filecoin Vision restrict big miners?

No, but to a certain extent, FILV will try to formulate on-chain rules to encourage miners to diversify their storage power to different miner addresses. FILV does not want to fall into the arms race of increasing garbage data accumulation, and should promote healthy competition and reduce carbon emissions.
