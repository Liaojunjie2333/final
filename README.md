# Final Project
|发布日期 | 2019-12-10 | 
-|-|
项目名称| 博物馆自助购 | 
项目现状| 进行中| 
项目所有者| 廖俊杰| 
项目设计师| 廖俊杰| 
项目开发者|廖俊杰| 
项目测试者| 廖俊杰| 

## PartA. 价值主张设计

### （一）加值宣言
*** 
- 如今，人们的文化需求日益增长。越来越多的人喜欢到博物馆参观，以作消遣、也能拓宽视野。在博物馆内，游客可以购买相关纪念品、文创产品。但商品的出售的方式还是以“人工式售卖”为主，游客的购物流程还是较传统的，并不能方便快捷地完成购物流程。基于现状，我们将采用“阿里云——商品图片搜索API”来对博物馆商店进行加值。

- 主要：运用了以深度学习和机器视觉技术为核心的“商品图像搜索”服务中的“商品查找功能”——用户输入图片在商品图像库中搜索，找到所需商品的图片。即输入——商品图片，输出——图片中的商品信息。

- 次要：运用了同为“商品图像搜索”服务中的“商品推荐功能”——用户输入图片在商品图像库中搜索，可推荐同款或相似商品的图片。即输入——商品图片，输出——同款/相似商品信息。

### （二）核心价值宣言
***
基于用户的最基本需求，该产品能够解决游客自助购买周边商品的问题，同时提供商品推荐功能。

### （三）背景
***
作为文化传播的一种途径/方式，“博物馆出售周边产品”已经有所普及了。博物馆参观者可能想购买周边商品（博物馆纪念品、文创产品）以留作纪念、提升文化体验，但整个购物流程还是稍微比较复杂的。如果有一个产品（APP/小程序），能够简化游客购买博物馆周边商品，这也许能让游客对博物馆的体验有所提升。

### （四）目标用户
***
- 博物馆参观者


### （五）用户痛点宣言
***
- 场景1：想购买博物馆纪念品，但受人流量的影响，工作人员比较忙。
- 场景2：想购买多种不同的文创产品送给家人，但比较纠结，不知道该买哪些。

### （六）AI概率性考量
***
#### 阿里云-商品图像搜索服务——产品优势
- 搜索精度高：业内领先水平的深度学习算法，效果精准；
- 搜索效率高：结合超大规模聚类和量化索引技术，达到毫秒级响应；
- 支持海量数据：大规模检索引擎支持百亿级别数据；

#### 可能发生的问题（环境因素）
- 拍照者手机摄像头出现异常、故障；
- 拍照场景过于亮、过与暗；
- 商品未录入商品库；
- 网络出现异常；
#### 总结
- 该产品利用商品图像搜索技术，通过拍摄要购买的商品，能够返回商品信息（价格、商品余量等等）。在商品图像库中搜索的效果精准、搜索效率也是达到毫秒级响应，普遍情况下都可以使用。
- 该产品可能因环境因素而发生问题事件，但发生的概率较小——多为少数事件，对正面影响并不大。

### （七）用户需求列表
***
用户案例 | 对应标题 |  重要程度
-|-|-
用户想快速购买博物馆周边商品，简化购物流程。| 商品图像搜索-商品查找| 重要 |
用户想购买同类型周边商品，但不知道该买哪种。| 商品图像搜索-商品推荐| 次重要|


#### 具体应用场景
- 周末，大学生阿鑫与同学前往博物馆进行参观。他想从博物馆里买个纪念品以作纪念，但售卖区人比较多，但他发现旁边有一个自助购买周边产品的货柜。根据货柜的提示，他根据货柜的提示，进入“博物馆自助购”小程序。拍了自己想要的纪念品的图片，很快就看到了商品信息，并通过手机完成了结账等流程，付款后，便从货柜中拿到了自己想要的纪念品。

- 周末，大学生阿昊在博物馆纪念品店给家人挑选着有趣的文创产品。但有选择困难症的他，不知道该买哪几款比较好。于是，他在“博物馆自助购”小程序中拍了自己喜欢的产品的照片，得到了多款相似产品的推荐。阿昊觉得推荐的产品好像也不错，就在手机上完成了购物流程，成功地在自助购货柜中拿到了所购买的文创产品。

## PartB. 原型

### （八）产品结构图
***
- 若该网页的图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

#### （1）产品基础结构图

![产品基础结构图.png](https://upload-images.jianshu.io/upload_images/9455181-c8f12d5506f7a4b9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### （2）产品功能结构图

![产品功能结构图.png](https://upload-images.jianshu.io/upload_images/9455181-b984b12dc1a0b723.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### （3）产品信息结构图

![产品信息结构图.png](https://upload-images.jianshu.io/upload_images/9455181-3343777f7ce1b583.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### （九）产品使用流程图
***
- 若该网页的图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

![博物馆自助购.png](https://upload-images.jianshu.io/upload_images/9455181-47e203889ba76b64.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### （十）产品原型
***
- 若该网页的图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

#### （1）口头操作说明
#### * 操作说明-微信授权模块

![微信授权模块.png](https://upload-images.jianshu.io/upload_images/9455181-f95f279a8324222c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



#### * 操作说明-拍照搜索（商品图像搜索）模块

![拍照搜索01.png](https://upload-images.jianshu.io/upload_images/9455181-bf19d1a5177e8035.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索02.png](https://upload-images.jianshu.io/upload_images/9455181-dd14c1d41794db68.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索03.png](https://upload-images.jianshu.io/upload_images/9455181-49732efd9322e082.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索04.png](https://upload-images.jianshu.io/upload_images/9455181-2bd7b22e4ba6c937.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索05.png](https://upload-images.jianshu.io/upload_images/9455181-7a418c39bb450bf2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![拍照搜索06.png](https://upload-images.jianshu.io/upload_images/9455181-aae00848d2d53835.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



#### * 操作说明-购物车模块

![购物车模块.png](https://upload-images.jianshu.io/upload_images/9455181-580406b186e7fdad.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### * 操作说明-我模块

![我模块.png](https://upload-images.jianshu.io/upload_images/9455181-c25d919cbc6f90d3.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### （2）AI加值——交互及界面设计

- 在交互及界面设计的核心交互环节——【用户拍摄商品图片——手机自动扫描识别商品图片——返回商品信息列表】中，使用了人工智能的加值，即使用了【商品图像搜索】服务的加值。

- 详情可参考[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)或上方的【操作说明-拍照搜索模块】。

#### （3）AI加值——信息设计

- 在信息设计的核心信息或设计——【扫描识别框、商品实物图】中，使用了人工智能的加值，即使用了【商品图像搜索】服务的加值。

- 详情可参考[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)或上方的【操作说明-拍照搜索模块】

#### （4）原型文档——展示、下载区

- [原型文档——展示](http://nfunm047.gitee.io/museum_self_purchase_prototype)

- [原型文档——下载地址](https://github.com/Liaojunjie2333/museum_self_purchase_prototype)


## PartC. API


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
- [产品价格](https://ai.baidu.com/docs#/IMAGESEARCH-Pricing/c2ba822b)（可查链接）


**API成熟度方面**：
- 已有应用案例：该服务已经应用在“当当网”、“健客网”、美玉秀秀APP等其他应用、平台上；

- 算法准确性高：基于数千万量级的训练数据、数万个语义类别进行模型训练及图库积累，使用精准的算法迭代模型不断提高准确度。

- 支持亿级超大图库：自建图库支持亿级图片量上传入库，实现实时检索，单图毫秒级响应。
- [产品优势](https://ai.baidu.com/tech/imagesearch/product)（可查链接）


#### （2）竞争对手分析：阿里云——图像搜索服务
 **API性价比方面**：
-  无每日免费调用额度；
-  采用购买按月（自然月）预付费资源包的计费方式；
- [产品价格](https://help.aliyun.com/document_detail/85153.html?spm=a2c4g.11186623.6.544.41133d28ru7FxY)（可查链接）

**API成熟度方面**：
- 搜索效率高：结合超大规模聚类和量化索引技术，达到毫秒级响应。
- 搜索精度高：业内领先水平的搜索服务。
- [产品优势](https://ai.aliyun.com/imagesearch?spm=5176.224200.h2v3icoap.194.4b1a6ed6KVRWe0&aly_as=I4K90Mri)（可查链接）

#### （3）总结
- **性价比方面**，百度方的调用性价比较高。首先，具有每日免费调用次数，在一定程度上节省了一定的成本；其次，提供“按调用量付费”的付费方式，使成本的可控制性更强，可避免浪费成本。而且，其接入服务简单易用，能够快速上手。

- **成熟度方面**，百度方和阿里方各有各的产品优势、技术优势，但百度方的产品已经有应用在市面上常见的平台上，可见其成熟度还是略胜一筹的。

### （十三）API使用后风险报告
***
所使用的API类别的现在及未来发展性

#### API市场竞争程度

#### 输入输出限制

#### 定价

#### 可替代的程序库（改用自己开发的代码及数据库而不用API）

