## 这是一个基于vue全家桶+node.js+express+mysql实现的商城网站

注意：本项目只是一个个人demo，只用于学习交流，故不在维护！

项目github地址：[mall](https://github.com/xuzhaopeng01/mall)

如果觉得对您有帮助，您可以在右上角给我个star支持一下，谢谢！


### 项目运行
```
# 克隆到本地：
https://github.com/xuzhaopeng01/mall.git

# 安装依赖：
vue:
....
cd mall(进入项目文件下)
npm install （安装依赖）

express:(进入项目文件下)
cd server
npm install（安装依赖）

# 本地开发，开启服务器，浏览器访问http://localhost:8080,express监听的是3001端口http://localhost:3001
vue:
npm run dev

express:
node bin\www

# 构建生产
npm run build
```
注：第一次使用vue和express的小伙伴记得全局安装下vue-cli和express
- **vue-cli**

### 项目说明
- 用到的技术栈

    vue-cli2 + vue2.0 + vue-router + vuex + axios + stylus + scss + node.js + es6 + express + mysql
- 实现功能

```
    - 登录注册
    - 商品详情
    - 购物车管理
    - 地址管理
    - 模拟支付（由于调用不了支付接口）
    - 订单管理
    
```
- 功能说明
```
    - 基于vue2.0
    - 使用vue-cli脚手架搭建项目
    - 使用vue-router实现路由切换
    - 使用vuex进行状态管理
    - 使用axios进行数据请求
    - stylus和scss编写样式
    - 联动滚动借助了vue-infinite-scroll插件和图片懒加载vue-lazyload插件
    - Express编写后台api
    - Mysql实现数据存储
 ```
 ### 学习参考
 - vue2.0官网 [https://vuefe.cn/v2/guide/](https://vuefe.cn/v2/guide/)
 - npm  [https://www.npmjs.com/](https://www.npmjs.com/)
 - ES6 [http://es6.ruanyifeng.com/](http://es6.ruanyifeng.com/)
 - Sticky footers [https://juejin.im/post/5a52d62a518825734c5b3c37](https://juejin.im/post/5a52d62a518825734c5b3c37)
 - awesome-vue [https://github.com/vuejs/awesome-vue](https://github.com/vuejs/awesome-vue)
 
