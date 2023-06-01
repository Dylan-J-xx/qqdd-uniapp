# qqdd-Uniapp

#### 介绍


#### 如何使用uni-app端

##### 一、导入uniapp项目

    1. 首先下载HBuilderX并安装，地址：https://www.dcloud.io/hbuilderx.html
    2. 打开HBuilderX -> 顶部菜单栏 -> 文件 -> 导入 -> 从本地目录导入 -> 选择uniapp端项目目录
    3. 找到common/config.js文件，找到里面的apiUrl项，填入已搭建的后端url地址
    4. 打开manifest.json文件，选择微信小程序配置，填写小程序的appid

##### 二、本地调试

    1. 打开HBuilderX -> 顶部菜单栏 -> 运行 -> 运行到浏览器 -> Chrome
    2. 如果请求后端api时 提示跨域错误，可安装Chrome插件：【Allow CORS: Access-Control-Allow-Origin】，地址：https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf

##### 三、打包发行（H5）

    1. 打开HBuilderX -> 顶部菜单栏 -> 发行 -> 网站H5-手机版
    2. 打包后的文件路径：/unpackage/dist/build/h5
    3. 将打包完成的所有文件 复制到商城后端/pulic目录下，全部替换

##### 四、打包发行（微信小程序）

    1. 下载微信开发者工具并安装，地址：https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html
    2. 打开HBuilderX -> 顶部菜单栏 -> 发行 -> 小程序-微信
    3. 打包后的文件路径：/unpackage/dist/build/mp-weixin
    5. 打开微信开发者工具 导入 打包完成的项目
    6. 检查没有运行错误，在右上方上传小程序


#### uniapp知识

1. <a href="https://uniapp.dcloud.io/README" target="blank">uni-app介绍</a>
2. <a href="https://ke.qq.com/course/3169971" target="blank">uni-app 官方视频教程</a>
3. <a href="https://www.dcloud.io/hbuilderx.html" target="blank">uni-app开发工具 HBuilderX 下载及使用说明</a>
4. <a href="http://ask.dcloud.net.cn/article/35657" target="blank">uni-app是什么？能解决什么问题</a>
5. <a href="https://uniapp.dcloud.io/vue-basics" target="blank">Vue.js相关文档、视频教程</a>

#### 技术手册

* <a href="https://uniapp.dcloud.io/collocation/pages" target="blank">uni-app 框架文档</a>
* <a href="https://uniapp.dcloud.io/component/README" target="blank">uni-app 组件文档</a>
* <a href="https://uviewui.com/components/intro.html" target="blank">uView 组件文档</a>
* <a href="https://uviewui.com/js/intro.html" target="blank">uView JS 文档</a>

#### 授权许可协议条款

本软件基于Ruoyi-Uniapp手机端

