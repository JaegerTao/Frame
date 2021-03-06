# Frame

## 基于uni-app的小程序快速搭建框架

通过本框架可以快速搭建起一个基于uni-app的微信小程序基础项目。

目前框架没有加入小程序分包示例，将在后续更新中推出。

- ### 运行工具


推荐使用HbuilderX进行uni-app项目开发。

使用微信开发者工具进行微信小程序端调试。

使用HbuilderX打开本项目根目录，在运行设置中配置好微信开发者工具的安装路径，

并在开发者工具的设置中，设置服务端口打开 和 使用系统代理。

- ### 使用方法


```js
npm run dev
```

或直接使用HbuilderX的运行按钮启动。

- ### manifest.json


微信开发需配置微信小程序配置，填写微信小程序的APPID，在微信开发者工具中使用小程序的开发者角色权限微信号进行登录

- ### 项目UI框架


本项目引入了colorUI框架，这是一款基于css的UI框架，支持许多基础样式的实现，使用方式详见DCloud插件市场中的ColorUI-UniApp前端模板。

- ### 本项目使用了less


本框架中使用了less/scss预处理器，请在项目运行前通过DCloud插件市场引入less和scss插件。

如果不需要使用less/scss，只需要css，那么可以在包含下方代码的示例页面和组件中

```css
<style lang="less" scoped>

</style>
```

将 lang = "less"删除掉即可。

- ### 推荐阅读文档或示例模板

微信小程序官方文档：https://developers.weixin.qq.com/miniprogram/dev/framework/

uni-app官方文档：https://uniapp.dcloud.io/

ColorUI-UniApp前端模板：https://ext.dcloud.net.cn/plugin?id=239

DCloud插件市场：https://ext.dcloud.net.cn/

w3cschool中的Less文档：https://www.w3cschool.cn/less/functions.html
