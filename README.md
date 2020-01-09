# wx-manage
微信公众号后台[wx-api](https://github.com/niefy/wx-api)项目管理系统界面，提供公众号菜单、自动回复、公众号素材、简易CMS、等管理功能


## 开发环境
- node.js

## 启动步骤
1. 启动[wx-api](https://github.com/niefy/wx-api)项目,具体流程参考对应项目介绍
2. 安装依赖

``` bash
npm install
```
2. 编译构建
``` bash
# 开发环境
npm run serve

# 生产环境
npm run build
```
3. 浏览器打开如下地址：
    - 首页：http://localhost:8001
    - 登录账号：admin / 123456


## 技术选型：
- 页面交互：[Vue2.x](https://cn.vuejs.org/v2/guide/)
- UI框架：[ElementUI](https://element.eleme.cn/#/zh-CN/component/quickstart)
- 后台模板：[renren-fast-vue](https://gitee.com/renrenio/renren-fast-vue)
- 富文本编辑器：[tinymce5](https://www.tiny.cloud/docs/quick-start/)

## 截图
![公众号菜单](https://raw.githubusercontent.com/niefy/wx-manage/master/screenshoot/菜单管理.png)
![带参二维码](https://raw.githubusercontent.com/niefy/wx-manage/master/screenshoot/带参二维码.png)
![文章编辑](https://raw.githubusercontent.com/niefy/wx-manage/master/screenshoot/文章编辑.png)
![自动回复](https://raw.githubusercontent.com/niefy/wx-manage/master/screenshoot/自动回复.png)


# 开发进度
- [x] 公众号菜单管理
    - [x] 与微信端公众号一致的可视化界面
    - [x] 支持配置链接、点击事件、小程序等多种菜单
- [x] 公众号自动回复（使用更灵活的客服消息接口做自动回复）
    - [x] 支持配置关注事件、扫描带参二维码、接受消息等场景自动回复
    - [x] 支持一个事件或一条消息进行多次回复
    - [x] 模糊匹配、多关键词、可配置时段
    - [x] 文字回复
    - [x] 图片、语音、视频、图文素材等媒体形式回复
    - [x] 回复小程序卡片、回复菜单消息
- [x] 公众号带参二维码管理
    - [x] 可配置临时带参二维码、永久带参二维码
- [x] 公众号素材管理
    - [x] 上传图片、语音、视频素材,获取素材media_id
    - [x] 获取公众号图文素材
    - [ ] 添加公众号图文素材
- [ ] 公众号用户管理
- [ ] 模板消息
- [x] 后台权限管理
    - [x] 可配置权限
    - [x] 动态后台菜单
    - [x] 数据字典
    - [x] 腾讯云、阿里云、七牛云对象存储
- [x] CMS文章
    - [x] 后台富文本文章编辑
    - [x] 微信端文章展示
- [x] 微信端
    - [x] 微信授权登录
    - [x] 微信分享
- [ ] 微信卡券
- [ ] 客服管理

## 开发交流
QQ群：732633965
进群密码：wx