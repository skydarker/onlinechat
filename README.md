<!--
 * @Author: 谈阿胜
 * @Date: 2022-08-31 17:10:46
 * @LastEditTime: 2022-09-29 09:56:46
 * @filePath: Do not edit
 * @one-word: 骑士有句老话，千里路途我只陪他一程，从此风雪艳阳我都不在过问
-->
# vue-im
神工坊客服系统。包括服务端和客户端。

# Features
* 支持1客服对多用户
* 支持客户选择客服
* 输入框支持文本、图片、表情、文件传输
* 输入框支持粘贴图片、文本表情混合

## im-server im服务端
![image](https://user-images.githubusercontent.com/3334204/54471439-e1a7b400-47f3-11e9-8a97-819ef99a0fb5.png)

## im-client im客户端
![image](https://user-images.githubusercontent.com/3334204/54471440-e704fe80-47f3-11e9-9454-96a2fb27b122.png)

## env&&RUN
```
npm install .

npm run dev
```
## Express-server
./build/webpack.dev.conf.js 内置了一个Express服务，后台接口都在此处



## Browser
目前只适配了Chrome浏览器

## LICENSE





## 个人分析各个文件的用处

> ```
> -assets(表情包)
> -build(nodejs的express框架)
> -config(配置文件)
> -src
> 
> ​	---assets(表情包)
> ​	---common(css样式)
> ​	---components组件(包含了一些客服端和服务端的页面)
> 
> ​		------login(管理员的登录和注册页面在里面，还未曾进行vue组件化)
> 
> ​		------imClient(客户端页面，可修改)
> 
> ​		------imServer(服务端页面，可修改)
> 
> ​		------common(公用的一些组件页面)
> ​	---router(路由)
> ​	---store
> 
> -static(样式外加socket通信)
> ```
>
> 
