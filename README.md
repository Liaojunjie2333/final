# Final Project
|发布日期 | 2019-12-10 | 
-|-|
项目名称| 博物馆自助购 | 
项目现状| 已完成 | 
项目所有者| 廖俊杰| 
项目设计师| 廖俊杰| 
项目开发者|廖俊杰| 
项目测试者| 廖俊杰| 


### 多版本价值主张写作
***
#### 1句话版本

- 基于用户的最基本需求，该产品能够解决【博物馆参观者购买纪念品/文创产品效率较低】的问题，简化购物流程，同时提供商品推荐功能。

#### 1分钟版本

- 在博物馆内，博物馆参观者可以购买纪念品或文创产品。但博物馆商品的出售方式还是以“人工售卖”为主，整个购物流程还是比较传统的，参观者并不能方便快捷地完成购物。比方说，参观者想购买博物馆纪念品，但因人流量太大、工作人员比较忙，无法快速购买纪念品。又或者说，参观者想购买不同的文创产品送给家人，但比较纠结，不知道该买哪些好。针对以上问题，我们将采用“百度AI——商品图片搜索API”来对博物馆纪念品店进行加值。我们将提供一款“博物馆自助购”小程序。通过这个小程序，博物馆参观者可以通过拍摄商品实物图，得到相同的商品信息，进而在小程序上快速完成购物流程。与此同时，博物馆参观者也能得到商品购买推荐。

#### 400秒版本

- 在线投影片在上方（文件处）可下载查看；

## Part A. 价值主张设计

### （一）加值宣言
*** 

- 如今，人们的文化需求逐渐上升。越来越多人喜欢到博物馆里进行参观，以作消遣、拓宽视野。在博物馆内，博物馆参观者可以购买纪念品或文创产品。但博物馆商品的出售方式还是以“人工售卖”为主，整个购物流程还是比较传统的，参观者并不能方便快捷地完成购物。基于现状，我们将采用“百度AI——图像搜索服务——商品图片搜索API”来对博物馆纪念品店进行加值。

- 主要：运用了以深度学习和机器视觉技术为核心的“图像搜索”服务中的“商品图片搜索”——“商品查找”功能——用户输入图片在商品图像库中搜索，找到所需商品的图片。即输入——商品实物图片，输出——同款/相似的商品信息。

- 次要：运用了“图像搜索”服务中的“商品图片搜索”——“商品推荐”功能——用户输入图片在商品图像库中搜索，可推荐同款或相似商品的图片。即输入——商品实物图片，输出——同款/相似商品信息。

### （二）核心价值宣言
***
基于用户的最基本需求，该产品能够解决【博物馆参观者购买纪念品/文创产品效率较低】的问题，简化购物流程，同时提供商品推荐功能。

### （三）背景
***
作为文化传播的一种途径/方式，“博物馆出售周边产品”已经有所普及了。博物馆参观者可能想购买周边商品（博物馆纪念品、文创产品）以留作纪念、提升文化体验，但整个购物流程还是稍微比较传统，购物流程并不便捷。如果有一个产品（APP/小程序），能够简化参观者购买博物馆周边商品，这也许能让参观者对博物馆的体验有所提升。

### （四）目标用户
***
- 博物馆参观者


### （五）用户痛点宣言
***

- 场景1：想购买博物馆纪念品，但因人流量太大、工作人员比较忙等原因，无法快速购买纪念品。
- 场景2：想购买不同的文创产品送给家人，但比较纠结，不知道该买哪些好。

### （六）AI概率性考量
***
#### 百度AI-图像搜索服务-商品图片搜索——产品优势

- 算法准确性高：基于数千万量级的训练数据、数万个语义类别进行模型训练及图库积累，使用精准的算法迭代模型不断提高准确度；
- 支持亿级超大图库：自建图库支持亿级图片量上传入库，实现实时检索，单图毫秒级响应；
- 服务简单易用：标准化接口封装，提供丰富的HTTP SDK，配套可视化图库管理后台，接入简单，快速上手；

#### 可能发生的问题（环境因素）

- 拍照者手机摄像头出现异常、故障；
- 拍照场景过于亮、过与暗；
- 商品未录入商品库；
- 网络出现异常；

#### 总结

- 该产品【博物馆自助购】运用【图像搜索服务——商品图片搜索】进行了加值。用户拍摄想要购买的纪念品，小程序能够自动返回商品信息（图片、价格、商品余量等等）供用户进行下一步操作。另外，在商品图像库中搜索的效果精准、搜索效率也是达到毫秒级响应，普遍情况下都可以使用。

- 该产品可能因环境因素而发生问题事件，但发生的概率较小——多为少数事件，对正面影响并不大。

### （七）用户需求列表
***

用户案例 | 对应标题 |  重要程度
-|-|-
用户想快速购买博物馆纪念品，简化购物流程。| 商品图片搜索| 重要 |
用户想购买同类型周边商品，没有推荐的情况下，不知道该买哪种。| 商品图片搜索| 次重要|


#### 具体应用场景
- 周末，大学生阿鑫与同学前往博物馆进行参观。他想在博物馆里买个纪念品以作纪念，但售卖区人比较多。这时，他发现旁边有一个自助购买纪念品的货柜。他根据货柜的操作提示，进入“博物馆自助购”小程序，拍了自己想要购买的纪念品的实物图片。他很快就看到了商品信息，并通过手机完成了结账等流程。付款后，阿鑫便从货柜中拿到了自己想要的纪念品。

- 周末，大学生阿昊在博物馆纪念品店给家人挑选着有趣的文创产品。但有选择困难症的他，不知道该买哪几款比较好。于是，他在“博物馆自助购”小程序中拍了自己喜欢的产品的照片，得到了多款相似产品的推荐。阿昊觉得推荐的产品好像也不错，就在手机上完成了购物流程，成功地在自助购货柜中拿到了所购买的文创产品。

## Part B. 原型

### （八）产品结构图
***
- 若图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

#### （1）产品基础结构图

![产品基本结构图.png](https://upload-images.jianshu.io/upload_images/9455181-8119ea8bb6552c51.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### （2）产品功能结构图

![产品功能结构图.png](https://upload-images.jianshu.io/upload_images/9455181-354496c0284fe3f8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### （3）产品信息结构图

![产品信息结构图.png](https://upload-images.jianshu.io/upload_images/9455181-fa76d52cf6aec398.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### （九）产品使用流程图
***
- 若图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

![使用流程图.png](https://upload-images.jianshu.io/upload_images/9455181-20b03e9c6a2a6769.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### （十）产品原型
***
- 若原型图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

#### （1）口头操作说明

![微信授权模块.png](https://upload-images.jianshu.io/upload_images/9455181-2803bd75d29e4c65.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

***

![拍照搜索01.png](https://upload-images.jianshu.io/upload_images/9455181-73a0e78102d5073d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索02.png](https://upload-images.jianshu.io/upload_images/9455181-224abbcaf68e3b91.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索03.png](https://upload-images.jianshu.io/upload_images/9455181-bd41c6257b775f02.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索04.png](https://upload-images.jianshu.io/upload_images/9455181-5bb0810a522c622e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索05.png](https://upload-images.jianshu.io/upload_images/9455181-456e1282a2b0f315.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索06.png](https://upload-images.jianshu.io/upload_images/9455181-26359f3a3d192975.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

***

![相册图片搜索01.png](https://upload-images.jianshu.io/upload_images/9455181-6d82e8e1684d0b37.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![相册图片搜索02.png](https://upload-images.jianshu.io/upload_images/9455181-fce5b07dad2fdf44.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![相册图片搜索03.png](https://upload-images.jianshu.io/upload_images/9455181-241ca302d85894f2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![相册图片搜索04.png](https://upload-images.jianshu.io/upload_images/9455181-c5ae18c80ba48e51.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索04.png](https://upload-images.jianshu.io/upload_images/9455181-5bb0810a522c622e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索05.png](https://upload-images.jianshu.io/upload_images/9455181-456e1282a2b0f315.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索06.png](https://upload-images.jianshu.io/upload_images/9455181-26359f3a3d192975.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


***

![购物车模块.png](https://upload-images.jianshu.io/upload_images/9455181-e6a8f9c7703ce756.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

***

![我模块.png](https://upload-images.jianshu.io/upload_images/9455181-4d4da174c8322b16.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### （2）AI加值——交互及界面设计

- 在交互及界面设计的核心交互环节——【用户拍摄博物馆纪念品图片——手机自动扫描搜索对应的纪念品图片——返回同款/相似纪念品信息列表】中，使用了人工智能的加值，即使用了【图像搜索服务——商品图片搜索】的加值。

- 输入：商品（博物馆纪念品）图片

- 输出：同款/相似商品（博物馆纪念品）信息

- 详情可参考[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)或上方的【口头操作说明-搜索模块】。

#### （3）AI加值——信息设计

- 在信息设计的核心信息或设计——【博物馆纪念品实物图片】、【扫描搜索框】、【同款/相似纪念品信息列表】中，使用了人工智能的加值，即使用了【图像搜索服务——商品图片搜索】的加值。

- 详情可参考[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)或上方的【口头操作说明-搜索模块】

#### （4）原型文档——展示、下载区

- [原型文档——展示](http://nfunm047.gitee.io/museum_self_purchase_prototype)

- [原型文档——下载地址](https://github.com/Liaojunjie2333/museum_self_purchase_prototype)


## Part C. API


### （十一）API的使用水平
***
- API：百度AI——图像搜索服务——商品图片搜索
- HTTP 方法：POST

- 请求URL： https://aip.baidubce.com/rest/2.0/image-classify/v1/realtime_search/product/search

- 输入：要进行检索的商品图片
```
# encoding:utf-8

import requests
import base64

'''

'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/realtime_search/product/search"
# 二进制方式打开图片文件
f = open('[本地文件]', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '[调用鉴权接口获取的token]'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())

```

-  输出：相关性最大的商品图片摘要信息（可关联至图库中的图片id/图片url）

```
{
    "result_num": 1,
    "result": [
        {
            "score": 0.97976700290421, #图片相关性，取值范围0-1，越接近1代表越相似
            "brief": "./data/jay1.jpg",  #入库时添加的brief信息（可关联至本地图库的图片id或者图片url）
            "cont_sign": "475124309,1080176642"  #图片签名，可以用来删除图片或定位问题
        }
    ],
	"has_more" : "false",
    "log_id": 1968648150
}

```
### （十二）API的使用比较分析
***
#### （1）自身分析：百度AI——图像搜索服务

**API性价比方面**：

- 具有每日免费调用额度 ，且通付费后，每日免费调用额度仍保留；

- 可选择“按调用量付费”进行API调用；

- “次数包”接口调用低至4元/千次；

- 标准化接口封装，提供丰富的HTTP SDK，配套可视化图库管理后台，接入简单，快速上手；

- 可查链接：[百度AI——图像搜索服务——产品价格](https://ai.baidu.com/docs#/IMAGESEARCH-Pricing/c2ba822b)


**API成熟度方面**：

- 已有应用案例：该服务已经应用在“当当网”、“健客网”、美玉秀秀APP等其他应用、平台上；

- 算法准确性高：基于数千万量级的训练数据、数万个语义类别进行模型训练及图库积累，使用精准的算法迭代模型不断提高准确度；

- 支持亿级超大图库：自建图库支持亿级图片量上传入库，实现实时检索，单图毫秒级响应。

- 可查链接：[百度AI——图像搜索服务——产品优势](https://ai.baidu.com/tech/imagesearch/product)


#### （2）竞争对手分析：阿里云——图像搜索服务

 **API性价比方面**：
 
- 无每日免费调用额度；

- 采用购买按月（自然月）预付费资源包的计费方式；

- 可查链接：[阿里云——图像搜索服务——产品价格](https://help.aliyun.com/document_detail/85153.html?spm=a2c4g.11186623.6.544.41133d28ru7FxY)

**API成熟度方面**：

- 搜索效率高：结合超大规模聚类和量化索引技术，达到毫秒级响应；

- 搜索精度高：业内领先水平的搜索服务。

- 可查链接：[阿里云——图像搜索服务——产品优势](https://ai.aliyun.com/imagesearch?spm=5176.224200.h2v3icoap.194.4b1a6ed6KVRWe0&aly_as=I4K90Mri)

#### （3）总结

- **性价比方面**，百度方的调用性价比较高。首先，具有每日免费调用次数，在一定程度上节省了一定的成本；其次，提供“按调用量付费”的付费方式，使成本的可控制性更强，可避免浪费成本。而且，其接入服务简单易用，能够快速上手。

- **成熟度方面**，百度方和阿里方各有各的产品优势、技术优势，但百度方的产品已经有应用在市面上常见的平台上，可见其成熟度还是略胜一筹的。

### （十三）API使用后风险报告
***
所使用的API类别：**图像搜索**

#### 面临的挑战

- 图像内容特征难以准确表达,即计算机的模型算法对图像特征的表达与人在视觉上的感知存在差异性,降低了图像搜索的准确率;

- 近似近邻搜索算法中,单一度量函数对图像内容特征相似度结果存在偏差导致准确率下降问题仍需研究;

- 目前国内外图像搜索的应用引擎大多是基于文本的方式,图像搜索结果存在不相关的情况较多。

- 参考链接：[基于深度学习的图像搜索系统研究与实现](http://cdmd.cnki.com.cn/Article/CDMD-10013-1019114262.htm)

#### 目前和未来发展性

- “图像搜索”的主要应用场景还是在目前较为常见、火爆的“电商场景”。随着时代的更替，电商平台的普及率越来越高，生产者和消费者的更多需求也是接踵而至。
“图像搜索”服务所提供的功能在很大程度上方便了平台参与者，因此，其目前发展性还是挺好的。

- 发展方向：从“以图搜图”延伸至“索引城市”；

- 杭州城市大脑视觉智能负责人——华先胜表示：图像搜索的下一步是可以索引整个城市；

> “搜索和挖掘，我们可以把城市里面我们通过摄像头看到的所有的视觉对象，放到搜索引擎里面去，就像商品搜索一样，就像其他的图像搜索引擎一样，车、人全都放进去，不仅仅是车牌、车的属性，甚至通过车特的图像，车、人的视觉特征进行搜索，这也是在业界也是非常难的一个问题，这叫车和人ID的问题，没有车牌没有人脸的时候大量的其实是看不清人脸的，能不能做到人的识别。”

- 参考链接：[阿里iDST研究员华先胜：图像搜索的下一步是可以索引整个城市](https://blog.csdn.net/weixin_34253539/article/details/86723693)

- 参考链接：[杭州城市大脑现交通行业论坛 视觉智能负责人华先胜分享大规模视频智能分析经验](http://baijiahao.baidu.com/s?id=1596073201469481322&wfr=spider&for=pc)

#### API市场竞争程度

- 目前API市场上，提供“图像搜索”这一API接口服务的大公司还是比较多的，例如百度、阿里、腾讯、微软等等；
- 各大服务商所提供的“图像搜索”类产品，各有各的产品特色、优势，我们也不能够随便地否定某个服务商，只能根据API使用者的需求、成本预算去进行选择；
- 用户在各大场景的相关痛点越来越多，为了能够吸引消费者，API服务提供商也是越来越多，各有各的产品优势，可以说是竞争比较激烈的。



