IOT-platform
============

An opensource IOT-platform for internet of the things.Using MQTT,CoAP,WebSocket,HTTP REST API

SmartLinkCloud
SmartLinkCloud.com

Author:quanpower
Email:quanpower@gmail.com

---------------------------------
####IOT-MQTT#####

1.安装依赖库

    npm install mqtt
    npm install mosca bunyan -g

2.启动mosca

    mosca -v | bunyan

3.测试mqtt-client

    node mqtt-subscribe-client.js
    node mqtt-publish-client.js
