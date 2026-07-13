从0到1试一下小程序

# 🚩背景介绍


# 🚩工作内容
## 1、💐环境准备
1、下载微信开发者工具：就在[微信官方文档-开发-工具](https://developers.weixin.qq.com/miniprogram/dev/devtools/download.html)

## 2、📖相关链接
### 微信
小程序、小游戏平台：[微信公众平台](https://mp.weixin.qq.com) \
小程序、小游戏开发文档：[微信官方文档](https://developers.weixin.qq.com/doc)

## 3、🤔方案调研

## 4、✍️开发
## 5、🔥问题Q&A
### Q：为啥小程序预览在手机上调取不了api，但是在开发者工具里面可以调用正常看效果呢？
A：
【project.config.json 之前是："urlCheck": false】所以开发者工具会绕过合法域名校验，看起来 API 正常；手机预览是真机环境，不会按这个绕过，所以就可能调不通。
【改成："urlCheck": true】这样开发者工具也会按真机规则校验，后面能提前发现域名问题。



# 🚩其他
## 1、⭐️注意事项
