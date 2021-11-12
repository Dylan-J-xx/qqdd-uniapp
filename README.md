# RuoYi-Uniapp（若依-手机端）开源啦

#### 介绍
&nbsp; &nbsp; 若依-Ruoyi APP 移动解决方案，基于 uniapp+uView 封装的一套基础模版，开箱即用，一份代码多终端适配，支持H5+支付宝小程序+微信小程序+APP，实现了与ruoyi-vue后台完美对接的移动解决方案，可直接开始快速开发业务需求，全新UI设计，更多交互细节，我们将为您提供极致的交互体验体验，持续推出高质量的交互产品。

    如果对您有帮助，您可以点右上角 “Star” 收藏一下 ，获取第一时间更新，谢谢！

#### 快速体验

2、微信小程序端：通过**微信**扫码<br><br>
<img src="https://jeesite.com/assets/images/wx_app.jpg" width="220" height="220" >

#### 如何使用uni-app端

##### 一、导入uniapp项目

    1. 首先下载HBuilderX并安装，地址：https://www.dcloud.io/hbuilderx.html
    2. 打开HBuilderX -> 顶部菜单栏 -> 文件 -> 导入 -> 从本地目录导入 -> 选择uniapp端项目目录
    3. 找到config.js文件，找到里面的apiUrl项，填入已搭建的后端url地址
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

#### 界面截图


<table>
    <tr>
        <td border = "10"><img src="https://images.gitee.com/uploads/images/2021/1112/184344_b519b98b_9700683.png" width="300" height="650"/>&nbsp;&nbsp;&nbsp;</td>
        <td><img src="https://images.gitee.com/uploads/images/2021/1112/184344_b519b98b_9700683.png" width="300" height="650"/>&nbsp;&nbsp;&nbsp;</td>
        <td><img src="https://images.gitee.com/uploads/images/2021/1112/184344_b519b98b_9700683.png" width="300" height="650"/>&nbsp;&nbsp;&nbsp;</td>
    </tr>
</table>

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

1. Ruoyi-Uniapp采用GPL3.0开源协议协议。
2. 代码可用于个人项目等接私活或企业项目脚手架使用，Ruoyi-Uniapp开源版完全免费。
3. 二次开发如用于商业性质或开源竞品请先联系群主审核。
4. 允许进行商用，但是不允许二次开源出来并进行收费，否则将追究侵权者法律责任。
5. 请不要删除和修改Ruoyi-Uniapp源码头部的版权与作者声明及出处。
6. 不得进行简单修改包装声称是自己的项目。
7. 我们已经申请了相关的软件开发著作权和相关登记
8. 不得将本软件应用于危害国家安全、荣誉和利益的行为，不能以任何形式用于非法为目的的行为。
6. 需要在您的软件介绍明显位置说明出处：举例：本软件基于Ruoyi-Uniapp手机端

#### 关于我们

&nbsp; &nbsp; 我们擅长UI、前端开发、后端架构，有一颗热爱开源的心，致力于打造企业级的通用产品设计UI体系让项目
或者更直观，更高效、更简单，未来将持续关注UI交互，持续推出高质量的交互产品。
######
<img src="https://images.gitee.com/uploads/images/2021/1112/114326_5eb079c2_9700683.jpeg" width="220" height="220" >&nbsp; &nbsp; &nbsp;&nbsp;
<img src="https://images.gitee.com/uploads/images/2021/1112/114207_bb1bac92_9700683.jpeg" width="220" height="220" >&nbsp; &nbsp; &nbsp;&nbsp; 
<img src="https://images.gitee.com/uploads/images/2021/1112/115039_4903466b_9700683.png" width="220" height="220" >&nbsp; &nbsp; &nbsp;&nbsp;

版权所有Copyright © 2017-2021 By AiDex (http://www.aidex.vip) All rights reserved。
