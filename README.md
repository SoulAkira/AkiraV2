# AkiraV2
+ Build for technical upgration, totally new solution for all infra.
+ Akira是一个社区运营小工具，匿名链上记录下社区有意义的人和事。
+ 发起活动-->提供底稿图片-->提供名单-->页面Serverless发布SBT
+ [测试链Demo]()
+ 目前所有发布在Polygon，gasfee由发布方支付，目前发布SBT还未添加接受方许可功能，默认进入名单的都接受SBT空投。


## History
+ [CSBS](https://github.com/PlanckerLabs/CSBS)
+ 重构所有基础架构，创新设计产品流程和交互，重写所有代码。

## Upgrade 
### Small version issues
+ 1.图片先生成到本地，id开头，然后生成metadata.json

+ 1.1上传到ipfs

+ 2.然后更改合约的baseTokenUrl?

+ 3.然后批量发布SBT：issueBatchSBTWithEvent

+ 4.对页面显示进度的地方，可以加个计数器

### Plan issues
+ 独立创建活动页面和流程，包括基础的图片底稿上传和合成
+ 独立的DAOStar集成流程（社区创建遵守DAOStar标准）
+ 单方面burn SBT功能（接受方解除或者擦除记录）
+ 部署到IPFS，独立free运营
+ IPFS的存储请求付费的grant接受
+ 开发维护人员的grant接受

### Tech
+ React
+ Tailwind
+ ThirdWeb(Wagmi)
+ Solidity
+ To be discuss
