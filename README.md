IOT-platform
============

An opensource IOT-platform for internet of the things.Using MQTT,CoAP,WebSocket,HTTP REST API
智联网云平台，使用MQTT,CoAP,WebSocket,HTTP REST API做底层数据处理。
---------------------------------

#智联网云平台


这是我们SmartLinkCloud物联网云平台的核心数据处理底层，欢迎使用及共同开发完善。
Author:quanpower，

Email:quanpower@gmail.com，

QQ群：152853091

SmartLinkCloud
SmartLinkCloud.com


##依赖库


##install



###安装node依赖

     npm install

###运行

     node server.js

###Test


##文档



## Liscense


[IOT-platform]: https://github.com/quanpower/IOT-platform
[SmartLinkCloud]: www.smartlinkcloud.com:3000 (测试中)

####IOT-MQTT#####

1.安装依赖库

    npm install mqtt
    npm install mosca bunyan -g

2.启动mosca

    mosca -v | bunyan

3.测试mqtt-client

    node mqtt-subscribe-client.js
    node mqtt-publish-client.js

4.测试mqtt-secure-client

    node mqtt-secure-server.js
    node mqtt-secure-client.js