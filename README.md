# 云开发 quickstart

这是云开发的快速启动指引，其中演示了如何上手使用云开发的三大基础能力：

- 数据库：一个既可在小程序前端操作，也能在云函数中读写的 JSON 文档型数据库
- 文件存储：在小程序前端直接上传/下载云端文件，在云开发控制台可视化管理
- 云函数：在云端运行的代码，微信私有协议天然鉴权，开发者只需编写业务逻辑代码

## 参考文档

- [云开发文档](https://developers.weixin.qq.com/miniprogram/dev/wxcloud/basis/getting-started.html)

要点一

页面布局flex

display: flex;

 flex-direction: column;

要点二

微信公众平台配置

服务域名配置方便进行，方便使用和风天气接口操作

存储data值  然后页面渲染值  

this.setData({

   region: e.detail.value

  })

要点四：

picker组件使用

