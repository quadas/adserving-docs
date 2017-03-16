# Index Of Quadas AD Serving Documents

# Get Ad

> 广告获取可以通过两种方式得到，一种是通过 API 提交合法参数，可直接获取到广告，此方法适合ServerToServer 将广告请求进行转发，另一种是通过传给 SDK 合法参数，由 SDK 获取到广告，并将结果返回给你，这种方式适用于在终端用户直接发起广告请求

| method | description |
|--------|--------|
|  direct      |  用户自行开发代码，在自己的Server 上中转终端广告请求，通过访问 Quadas 的 BidderServer 获取广告 , 详细接口参数见[文档](https://github.com/quadas/docs-ad-call/blob/master/mob.md)    |
| SDK| 使用 Quadas 的 SDK 包进行广告获取，使用方法参考[SDK4IOS]()；[SDK4Android]()；[SDK4Web](https://github.com/quadas/sdk4webjs/blob/master/document.md)|


# Adv Settings

> 可以对广告素材(campagin & line )进行 CURD，可以获取特定广告的详细执行数据，以及范围时间内的报表


| method | description |
|--------|--------|
|Quadas Console|使用预设账号密码登录 Quadas Web Console 进行创建和管理 |
|RESTful Api| 使用RESTful Api 方式进行广告资源的管理以及广告效果数据和相关报表数据，详细api参数见[文档]()|

# Publisher Settings

> 可以对广告位(publisher & placement)进行 CURD，可以获取特定广告位的曝光和点击数据，以及范围时间内的报表

| method | description |
|--------|--------|
|Quadas Console|使用预设账号密码登录 Quadas Web Console 进行创建和管理 |
|RESTful Api| 使用RESTful Api 方式进行广告位的管理以及CPM，CPC 的相关报表数据，详细api参数见[文档](https://quadas.github.io/slate/#introduction)|

