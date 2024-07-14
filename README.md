# 抖音开放平台第三方代小程序开发

https://mp.weixin.qq.com/s/s17zlz_vWeXqzRWTwPMeUw

![Image text](https://picx.zhimg.com/70/v2-ffecca6096e29b21604a6a8f9c17d17a_1440w.png)

#### 介绍
抖音小程序第三方平台开发着力于解决抖音生态体系内的小程序管理问题，一套模板，随处部署。能尽可能地减少服务商的开发成本，服务商只用开发一套小程序代码作为模板就可以快速批量的孵化出大量的商家小程序。

第三方平台是第三方服务商帮助小程序开发者进行开发、管理、运营等工作的综合平台。小程序开发者可一键授权给第三方平台，通过第三方平台完成业务。

![Image text](https://pic1.zhimg.com/80/v2-31c842e215ad0abdafc1bd7b3f6bdbc0_720w.png)

比如餐饮类、社区团购类的小程序，大部分功能都相同，这时第三方平台只要通过模板开发，得到商家授权后，即可快速根据模板代码给商家快速实例化小程序。无需关心各个商家的小程序资料信息，繁琐操作那些开发配置信息。多个前端只需对应一个服务端后台。时间少，成本低。

模板代开发的优势就是可以批量代开发/管理商家小程序，若服务商优化了模板小程序中的一个逻辑，则可以调用平台提供的功能批量构建、提审、上架所有已授权商家小程序。

业务特点：

开发流程：服务商先开发小程序模板的代码，然后通过小程序模板的代码去构建商家小程序的代码。

快速开通：通过服务市场，商家完成订购小程序，通过模板快速构建商家小程序版本。

批量维护：服务商可代商家实现小程序的快速批量更新。

![Image text](https://pic1.zhimg.com/80/v2-f382236f26d099de259b6545ffd680f0_720w.png)

代商家管理小程序功能主要包括基础信息管理、开发管理、运营管理。

基础信息管理

主要功能有商户授权、设置基本信息、服务类目管理、设置服务器域名、设置业务域名、查看质量评级信息、查看信用分分值、生成体验二维码、生成小程序码。

开发管理

主要功能有上传代码、提交审核、审核撤回、查看版本、发布小程序、版本回退。

运营管理

主要功能有申请短视频挂载能力、申请抖音直播组件能力、申请获取用户手机号能力。

#### 1、商家授权

商家跳转到授权页面，商家确认第三方小程序应用信息，选择要授权的小程序，勾选授权权限集，点击确定即可完成授权。

![Image text](https://pic4.zhimg.com/80/v2-eab9bb216fc17e2918bdde6087357823_720w.png)

![Image text](https://pic4.zhimg.com/80/v2-9a4d9261928056407d6315586f4b4913_720w.png)

#### 2、修改小程序基本资料

在这里可以直接修改小程序资料，而无需跑到各个小程序后台去修改。包括小程序头像、小程序名称、简介内容。这三个本来是独立功能，放在一起，所以修改的时候需要选择要修改哪个属性。

![Image text](https://pic3.zhimg.com/80/v2-4a57db8538d5cbc31245bbf046a9a43e_720w.png)

#### 3、服务类目管理

为授权小程序添加服务类目。由于小程序主体的不同（个人或企业），允许添加的服务类目也不同。每个小程序最多设置 5 个服务类目。在想要设置的服务类目允许的范围内，资质可以多传，但不能少传。

![Image text](https://pic2.zhimg.com/80/v2-b75e230785be12899ec7e82aae78ae69_720w.png)

![Image text](https://pic1.zhimg.com/80/v2-9b073588e644aea6472acc7af49d3e60_720w.png)

删除类目。

![Image text](https://pic4.zhimg.com/80/v2-0cffac79492f5a1ae79f03e74f5dbd77_720w.png)

新增类目，如果需要资质的话要上传资质文件。

![Image text](https://pic2.zhimg.com/80/v2-9f0a0823bc84032aa4681bb2e1c17eed_720w.png)

修改类目，如果被驳回后可以进行修改。

![Image text](https://pic2.zhimg.com/80/v2-38f4f5dcaf333ea2bade7a3d07b043ed_720w.png)

#### 4、设置服务器域名

为授权小程序修改服务器域名（request、socket、upload、download 域名）。授权给第三方的小程序，其服务器域名只可以为第三方的服务器。服务器域名需要在第三方小程序应用的服务器域名列表内或者是第三方小程序应用服务器域名的子域名。例如第三方登记的服务器域名如为http://douyin.com，则可以直接将http://douyin.com及其子域名（如http://xxx.douyin.com）也配置到授权的小程序中。

![Image text](https://pic4.zhimg.com/80/v2-774af5655e934a82db485ff675c0a377_720w.png)

支持添加、覆盖、删除、获取操作。

![Image text](https://pic3.zhimg.com/80/v2-fe4709a3b81233a4692391f11ce06a0e_720w.png)

#### 5、设置业务域名

为授权小程序修改业务域名（webview 域名）。授权给第三方的小程序，其业务域名只可以为第三方的服务器。域名需要在第三方小程序应用的 webview 域名列表内或者是第三方小程序应用 webview 域名的子域名。例如第三方登记的业务域名如为http://douyin.com，则可以直接将 http://douyin.com 及其子域名（如 http://xxx.douyin.com）也配置到授权的小程序中。

![Image text](https://pic2.zhimg.com/80/v2-4b85d9afdaaf8a3286e5f81dbc317e35_720w.png)

支持添加、覆盖、删除、获取操作。

![Image text](https://pic4.zhimg.com/80/v2-f5de5a24730abb4898c10b1462d584b3_720w.png)

#### 6、查询质量评级信息

为授权小程序查询质量评级信息。

![Image text](https://pic3.zhimg.com/80/v2-d45e2b294cf45e43a7e62e5c20fbdd9e_720w.png)

#### 7、查询信用分分值

为授权小程序查询信用分分值。

![Image text](https://pic3.zhimg.com/80/v2-1d5fc26d876b57c3c03c292d3b63d1f6_720w.png)

最重要的就是代小程序上传代码、提交审核、撤回审核、发布小程序、版本回退等功能。

#### 8、上传代码

为授权小程序提交代码。提交成功后，授权小程序具有测试版本。

![Image text](https://pic3.zhimg.com/80/v2-afeb20105e7c7f20c752f5255b615c6e_720w.png)

![Image text](https://pic4.zhimg.com/80/v2-3ce2d10698facff6287c3ff4d6ba346f_720w.png)

#### 9、提交审核

为授权小程序提审代码。当上传代码成后，在这里提交审核，审核成功后，授权小程序具有审核版本。

![Image text](https://pic2.zhimg.com/80/v2-ff35134223cd10cbde924413df154ea5_720w.png)

#### 10、审核撤回

为授权小程序撤回版本审核队列的待审版本。如果提交审核版本后发现问题，又不想等待审核被拒，可以使用该功能进行撤回。

![Image text](https://pic1.zhimg.com/80/v2-6bff67478c0d70f61c358307bae18b9c_720w.png)

#### 11、生成体验二维码

为授权小程序获取小程序对应版本阶段（测试版、审核版、线上版）的二维码。在审核发布之前可以生成体验二维码进行体验。对于线上版，二维码中不包含版本号的信息，所以不管发过多少次版本，生成的二维码都是一样的，并且扫码看到的都是最新版本的内容。

![Image text](https://pic3.zhimg.com/80/v2-b52fb3acf9f50d543226229354a48626_720w.png)

![Image text](https://pic4.zhimg.com/80/v2-511d962fb1f839054c5905941b2f22b3_720w.png)

#### 12、查看版本

为授权小程序获取小程序版本列表信息。包括线上版本、测试版本、审核版本三种版本信息。

![Image text](https://pic1.zhimg.com/80/v2-74c8198fbbcf445f53f563326a9f4fdc_720w.png)

#### 13、发布小程序

为授权小程序发布代码。审核通过之后，可以将版本发布。发布成功后，授权小程序具有线上版本。

![Image text](https://pic3.zhimg.com/80/v2-414cb4f66786dad79a28a55ce5a30352_720w.png)

#### 14、版本回退

为授权小程序回退代码版本。如果发现小程序上线后有问题，修复时间又比较长，可以先使用该功能将小程序代码包回退到上一个线上版本。

![Image text](https://pic4.zhimg.com/80/v2-1d3c66ddfca7f9b0a389ef8de9d0133f_720w.png)

#### 15、生成小程序码

为授权小程序获取线上版本的小程序码。该小程序码可通过任意 app 扫码打开，能跳转到开发者指定的对应字节系 app 内拉起小程序，并传入开发者指定的参数。通过该功能生成的小程序码，永久有效，暂无数量限制。

![Image text](https://pic1.zhimg.com/80/v2-24668389bf5e01b0634b13c1c52149bc_720w.png)

![Image text](https://pic1.zhimg.com/80/v2-7bd25c8316b68cdc6b231bab6a2cdaa4_720w.png)

#### 16、申请短视频挂载

为授权小程序申请「短视频挂载」能力，查询「短视频挂载」能力申请状态。

![Image text](https://pic4.zhimg.com/80/v2-2c316ec9183e58327fc41c8dcbe44be3_720w.png)

#### 17、申请抖音直播组件

为授权小程序申请「抖音直播组件」能力，查询「抖音直播组件」能力申请状态。

![Image text](https://pic1.zhimg.com/80/v2-5cf087133ca1fdd2192c678ceb4692f8_720w.png)

#### 18、申请获取用户手机号

为授权小程序申请「获取用户手机号」能力，查询「获取用户手机号」能力申请状态。

![Image text](https://pic1.zhimg.com/80/v2-df6a9949bb6aa2eb3e4fba751343c808_720w.png)

这就是抖音开放平台第三方代小程序开发，一整套流程。

![Image text](https://pic1.zhimg.com/80/v2-fc64ca6384d51bffb28eb6e100c1185c_720w.png)

山水有相逢，来日皆可期，谢谢阅读，我们再会

我手中的金箍棒，上能通天，下能探海
