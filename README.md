# final
##  项目：智能毕业相册APP

### 一、加值宣言
*** 
目前，市面上的“相册APP”的功能主要以存储、加密、分享为主，例如“时光相册”、“相册管家”、“动感相册”等等。基于现状，针对用户联系的需求，将采用“百度人脸识别API”、“高德web服务API——地理编码”、“高德web服务API——路径规划”这三个API产品对现有相册产品进行加值、优化。即：
- 用户输入一张图片（含被识别的主体），输出被识别主体的个人信息（如：微信账号）；
- 用户输入双方的地理坐标，输出最优导航线路；



### 二、核心价值宣言
***
基于用户的最基本需求，该产品能够满足用户联系“同窗”（老同学）的需求，同时提供“相聚”的路线推荐功能。

### 三、背景
***
目前，相册类应用的功能多以存储、分类、加密、分享为主。而针对毕业生这一群体，毕业相册常用于回忆过往的点滴，只能图个念想，并不能立马联系上老同学，即使是目前的相册类APP也无法实现联系对方的功能。那么，如果有一个智能的毕业相册，毕业生们在浏览毕业照的同时，也能够快速联系上对方，或与其相聚，毕业生们的念想便有机会化为现实。
### 四、目标用户
***
各阶段毕业生（小学、初中、高中、大学等）

### 五、用户痛点宣言
***
- 场景1：用户浏览着毕业相册时，想起过往的点滴，想要即刻联系上照片中的老同学；
- 场景2：用户之间(老同学之间)想要相聚，但不知道在哪聚会双方都比较方便；

### 六、用户需求列表
***
用户案例 | 对应标题 |  重要程度
-|-|-
用户想快速得到老同学的联系信息，与其进行联系 | 人脸检测 | 重要 |
用户想与老同学相聚，同时得到最优（便利双方）地点推荐 | 地理编码、路径规划 | 次重要|

#### 具体应用场景
- 毕业生小明翻看相册，看到与“死党”的合照想起过往点滴。无奈因学习、工作等原因，双方很久都没有联系了，内心想要联系其的冲动一涌而上。于是，小明打开了自己班级的智能毕业相册，识别毕业合照后，快速获取到“死党”的基本信息，联系上他了；
- 同班毕业生小明和小李两人过去是很好的“死党”，无奈因学习、工作等原因，双方很久都没有联系了，内心想要相聚的冲动一涌而上，但又不知道在哪相聚会便利双方。于是，他们打开了自己班级的只智能毕业相册，通过GPS定位邀请后，智能毕业相册给他们推荐了最优地点推荐。

### 七、产品结构图
***
![智能毕业相册产品结构图.png](https://upload-images.jianshu.io/upload_images/9455181-39af9d5670fc0ab2.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 八、产品使用流程图
***
![智能毕业相册使用流程图.png](https://upload-images.jianshu.io/upload_images/9455181-b9f5398479ee0459.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 九、产品原型展示
***
#### 1.【班级成员】模块
![【班级成员】.png](https://upload-images.jianshu.io/upload_images/9455181-532b337e2e6dfa02.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 2.【我】模块
![【我】.png](https://upload-images.jianshu.io/upload_images/9455181-e8a099ce7e7b5027.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 3.【照片识别】模块

![【识别1】.png](https://upload-images.jianshu.io/upload_images/9455181-3f82a2b7432aca46.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![【识别2】.png](https://upload-images.jianshu.io/upload_images/9455181-929bfab4457ebf0c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![【识别3】.png](https://upload-images.jianshu.io/upload_images/9455181-0c53dcc2b0e9fd01.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


### 十、API使用水平
***
- 百度人脸识别API-人脸检测
- 高德web服务API-地理编码
- 高德web服务API-路径规划
