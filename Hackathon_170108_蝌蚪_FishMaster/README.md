#养鱼专家(FishMaster)

![FishMaster](./FishMaster.png)

##简单介绍
* 基于Huawei LiteOS系统采用STM32F103单片机，单片机通过传感器采集鱼缸内温度、TDS等数据，经过处理后一方面发送给OLED显示屏进行显示，另一方面通过WIFI模块采用MQTT协议传输到百度IOT平台，手机app端同样采用MQTT协议和百度IOT平台连接获取温度、TDS等数据，进行分析，提醒用户水质、温度情况，同时还具有自动控制功能。

##养鱼专家解决的问题
* 养鱼前，没人指导怎么办？
* 养的鱼经常生病怎么办？
* 我们出差了，我们的鱼怎么办？

##图示

![FishMaster](./1.png)
![FishMaster](./2.png)
![FishMaster](./3.png)
