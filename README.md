# final
|发布日期 | 2019-12-10 | 
-|-|
项目名称| 博物馆自助购 | 
项目现状| 进行中| 
项目所有者| 廖俊杰| 
项目设计师| 廖俊杰| 
项目开发者|廖俊杰| 
项目测试者| 廖俊杰| 
### 一、加值宣言
*** 
- 如今，人们的文化需求日益增长。越来越多的人喜欢到博物馆参观，以作消遣、也能拓宽视野。在博物馆内，游客可以购买相关纪念品、文创产品。但商品的出售的方式还是以“人工式售卖”为主，游客的购物流程还是较传统的，并不能方便快捷地完成购物流程。基于现状，我们将采用“阿里云——商品图片搜索API”来对博物馆商店进行加值。

- 主要：运用了以深度学习和机器视觉技术为核心的“商品图像搜索”服务中的“商品查找功能”——用户输入图片在商品图像库中搜索，找到所需商品的图片。即输入——商品图片，输出——图片中的商品信息。

- 次要：运用了同为“商品图像搜索”服务中的“商品推荐功能”——用户输入图片在商品图像库中搜索，可推荐同款或相似商品的图片。即输入——商品图片，输出——同款/相似商品信息。

### 二、核心价值宣言
***
基于用户的最基本需求，该产品能够解决游客自助购买周边商品的问题，同时提供商品推荐功能。

### 三、背景
***
作为文化传播的一种途径/方式，“博物馆出售周边产品”已经有所普及了。博物馆参观者可能想购买周边商品（博物馆纪念品、文创产品）以留作纪念、提升文化体验，但整个购物流程还是稍微比较复杂的。如果有一个产品（APP/小程序），能够简化游客购买博物馆周边商品，这也许能让游客对博物馆的体验有所提升。

### 四、目标用户
***
- 博物馆参观者


### 五、用户痛点宣言
***
- 场景1：想购买博物馆纪念品，但受人流量的影响，工作人员比较忙。
- 场景2：想购买多种不同的文创产品送给家人，但比较纠结，不知道该买哪些。

### 六、AI概率性考量
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

### 七、用户需求列表
***
用户案例 | 对应标题 |  重要程度
-|-|-
用户想快速购买博物馆周边商品，简化购物流程。| 商品图像搜索-商品查找| 重要 |
用户想购买同类型周边商品，但不知道该买哪种。| 商品图像搜索-商品推荐| 次重要|


#### 具体应用场景
- 周末，大学生阿鑫与同学前往博物馆进行参观。他想从博物馆里买个纪念品以作纪念，但售卖区人比较多，但他发现旁边有一个自助购买周边产品的货柜。根据货柜的提示，他根据货柜的提示，进入“博物馆自助购”小程序。拍了自己想要的纪念品的图片，很快就看到了商品信息，并通过手机完成了结账等流程，付款后，便从货柜中拿到了自己想要的纪念品。

- 周末，大学生阿昊在博物馆纪念品店给家人挑选着有趣的文创产品。但有选择困难症的他，不知道该买哪几款比较好。于是，他在“博物馆自助购”小程序中拍了自己喜欢的产品的照片，得到了多款相似产品的推荐。阿昊觉得推荐的产品好像也不错，就在手机上完成了购物流程，成功地在自助购货柜中拿到了所购买的文创产品。


### 八、产品结构图
***
- 若该网页的图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

#### （1）产品基础结构图

![产品基础结构图.png](https://upload-images.jianshu.io/upload_images/9455181-c8f12d5506f7a4b9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


#### （2）产品功能结构图

![产品功能结构图.png](https://upload-images.jianshu.io/upload_images/9455181-b984b12dc1a0b723.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### （3）产品信息结构图

![产品信息结构图.png](https://upload-images.jianshu.io/upload_images/9455181-3343777f7ce1b583.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 九、产品使用流程图
***
- 若该网页的图片无法正常显示，请在[原型文档](http://nfunm047.gitee.io/museum_self_purchase_prototype)中查看。

![博物馆自助购.png](https://upload-images.jianshu.io/upload_images/9455181-47e203889ba76b64.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 十、产品原型
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

#### （3）AI加值——信息设计

#### （4）原型文档——展示、下载区
- [原型文档——展示](http://nfunm047.gitee.io/museum_self_purchase_prototype)

- [原型文档——下载地址](https://github.com/Liaojunjie2333/museum_self_purchase_prototype)
### 十一、API的使用水平
***
待完成...

### 十二、API的使用比较分析
***
待完成...

### 十三、API使用后风险报告
***
待完成...

