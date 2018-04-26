eos-medishares-testnet
==================================
eos-medishares-testnet(以下简称EOS-MDS测试网)是由medishares团队基于EOS DAWN 3.0创建的测试网络，该测试网旨在为开发者提供更好的线上开发环境。

EOS-MDS区块浏览
==================================
（待更新）

BP列表
==================================
| Producer Name | Host | HTTP Port | P2P Port| Location | Organisation |
| ------------- |:-------------:|:-----:|:---------:|:-----------:|-----------:|
| eosio     | eostestnet1.medishares.net| 8888 |9876| ShangHai | Medishares|
| panda     | eostestnet2.medishares.net| 8888 |9876| ShangHai | Medishares|
| wait for you |      |     |     |    |   |

加入EOS-MDS测试网
==================================
EOS-MDS测试网秉承开放、自由的原则，任何人都可以连接EOS-MDS测试网，您只需要：

1.搭建自己的节点环境；

2.下载配置文件并修改。

若要申请成为EOS-MDS测试网BP（Block Producer），请issues提交节点信息。

本地环境搭建
-----------------------------------
本地环境搭建请参考EOS官方社区的[Setting Up A Local Environment](https://github.com/EOSIO/eos/wiki/Local-Environment)，有比较详尽的介绍，如有任何疑问，欢迎进入[MDS电报群](https://t.me/medisharesCN)交流讨论。

连接EOS-MDS测试网
-----------------------------------
拷贝config.ini和genesis.json文件到配置文件目录（默认在/root/.local/share/eosio/nodeos/config/目录）,修改配置文件config.ini，配置如下参数：

p2p-server-address: 改成你自己的服务器IP和监听的p2p端口, 默认是 IP:9876；

agent-name: 改成你自己的节点标识, 域名或其他，用于区别测试网中其他节点；

private-key: 你的密钥对, 建议创建全新的；

producer-name: 节点账户名(随便填一个即可).

运行nodeos程序启动节点。

申请成为BP
-----------------------------------
通过上面步骤后，您已经成功连接到EOS-MDS测试网，若要申请成为BP，请issues提交如下信息，我们会第一时间将您加入BP列表。

1.Server Location

2.Organisation

3.Node ip/Domain

4.Port (http)

5.Port (p2p)

6.Producer name

7.Agent Name

8.Your public key

开发/测试工具
==================================
除EOS DAWN 3.0自带的cleos程序外，我们也推荐[EOSDevHelper](https://github.com/OracleChain/EOSDevHelper)图形化工具，提高操作的便利性。

交流讨论
==================================
如操作过程遇到任何问题，欢迎通过如下任一方式交流讨论。

EOSdata社区：http://eosdata.io/

Twitter: https://twitter.com/MediShares

Telegram: https://t.me/eosmedishares

Weibo: http://weibo.com/MediShares

