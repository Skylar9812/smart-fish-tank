```mermaid
graph TD
    A[智能鱼缸系统 Smart Fish Tank]

    A --> B[1 打氧功能 Oxygenation]
    B --> B1[要解决的问题：定时开关、远程控制、异常触发]
    B --> B2[使用器件：继电器、单片机MCU、ESP8266]

    A --> C[2 加热恒温 Heating]
    C --> C1[要解决的问题：检测水温、判断是否加热、安全控制]
    C --> C2[使用器件：DS18B20温度传感器、继电器、MCU、电源模块]

    A --> D[3 水质检测 Water Quality]
    D --> D1[要解决的问题：TDS检测、浊度判断、异常告警]
    D --> D2[使用器件：TDS模块、LED警告灯、MCU读取、ESP8266上传]

    A --> E[4 景观RGB灯光 RGB Lighting]
    E --> E1[要解决的问题：三原色控制、亮度调整、模式切换]
    E --> E2[使用器件：RGB LED模块、限流电阻、GPIO控制、MCU程序]

    A --> F[5 手机App交互 App Interaction]
    F --> F1[要解决的问题：数据上传、远程指令、状态反馈]
    F --> F2[使用器件：ESP8266 WiFi模块、MCU、OLED显示模块(可选)]
```
