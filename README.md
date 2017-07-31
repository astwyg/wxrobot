# wxrobot

一个非常简单的微信机器人, 向url发送http请求, 即可收到微信消息.

建议自己部署, 下面是一个部署好的机器人使用方法.

# 使用方法

## 按照下面方法发送请求:

GET:
```
http://www.6vdata.com/msg?to=<nickname>&content=<content>
```

POST:
```
http://www.6vdata.com/msg

form内容:
to:<nickname>
content:<content>
```

## 扫描二维码加机器人好友之后, 即可收到消息

![](https://raw.githubusercontent.com/astwyg/wxrobot/master/robot_qr.jpg)

