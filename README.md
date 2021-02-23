### 海风小店，开源商城（后台管理端VUE）

+ 基于开源项目NideShop重建，精简了一些功能的同时完善了一些功能，并重新设计了UI
+ 测试数据来自上述开源项目
+ 服务端api基于Ｎode.js+ThinkJS+MySQL
+ 后台管理 基于VUE.js+element-ui

### 目前基于海风小店已经上线的几款微信小程序商城
<img width="1400" src="http://git.hiolabs.com/miniapp.jpg"/>

#### 视频教程
https://www.bilibili.com/video/av89568075

#### 本项目需要配合  
服务端： https://github.com/iamdarcy/hioshop-server  
微信小程序：https://github.com/iamdarcy/hioshop-miniprogram

线上demo：http://hiolabs.com/demo/#/login  
用户名：hiolabs  
密码：hiolabs


### 项目截图
+ Dashboard

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/dashboard.jpg"/>

+ 订单

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/order.jpg"/>

+ 电子面单生成

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/express2.jpg"/>

+ 商品管理

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/goods.jpg"/>

+ 购物车

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/cart.jpg"/>

+ 用户

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/user.jpg"/>

+ 运费模板

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/template.jpg"/>

+ 运费模板详情页

<img width="900" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/template2.jpg"/>

### 本地开发环境配置
+ 克隆项目到本地
```
git clone https://github.com/LiangSenCheng/hioshop-admin
```
+ 安装依赖
```
npm install

```
安装依赖后启动后会出现一个问题。

<img width="600" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/error.jpg"/>

这个问题是Element-ui自带的。解决方法：

在node_modules 搜索:  div class="el-form-item__label-wrap" style={style}  
然后在语句中加上单引号就可以了。

<img width="600" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/before.jpg"/>

<img width="600" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/after.jpg"/>

+ 启动
```
npm run dev

```

+ build 打包成静态文件
```
npm run build:web 或者 sudo npm run build:web

```

生成的静态文件在dist的web文件夹中，上传到服务器就可以在浏览器中打开了。

### 功能列表
+ 订单管理：查看，修改订单价格，发货，生成电子面单，修改订单状态
+ 商品管理：添加、修改、删除商品，添加商品分类
+ 购物车：可以看到用户加入购物车的情况
+ 用户列表：用户的一些使用踪迹
+ 店铺设置：广告列表，公告管理，运费模板（可以根据地区设置相应的运费），管理员

### 最近更新 
- 新增生成分享图的功能
<img width="1000" src="https://cdn.jsdelivr.net/gh/LiangSenCheng/blog-img/img/save-local.jpg"/>

- 项目地址  
后台管理：https://github.com/iamdarcy/hioshop-admin  
服务端： https://github.com/iamdarcy/hioshop-server  
微信小程序：https://github.com/iamdarcy/hioshop-miniprogram  

