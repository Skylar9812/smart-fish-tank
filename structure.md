```mermaid
graph TD
    A[智能鱼缸系统 Smart Fish Tank] 

    A --> B[1. 打氧功能<br>Oxygenation]
    B --> B1[需要解决的问题<br>- 定时开关<br>- 远程控制<br>- 异常触发]
    B --> B2[使用器件<br>- 继电器<br>- 单片机MCU<br>- ESP8266]

    A --> C[2. 加热恒温<br>Heating]
    C --> C1[需要解决的问题<br>- 检测水温<br>- 判断是否加热<br>- 安全控制]
    C --> C2[使用器件<br>- DS18B20温度传感器<br>- 继电器<br>- MCU控制<br>- 电源模块]

    A --> D[3. 水质检测<br>Water Quality]
    D --> D1[需要解决的问题<br>- TDS检测<br>- 浊度判断<br>- 异常告警]
    D --> D2[使用器件<br>- TDS模块<br>- LED警告灯<br>- MCU读取<br>- ESP8266上传]

    A --> E[4. 景观RGB灯光<br>RGB Lighting]
    E --> E1[需要解决的问题<br>- 三原色控制<br>- 亮度调整<br>- 模式切换]
    E --> E2[使用器件<br>- RGB LED模块<br>- R10/11/12限流电阻<br>- GPIO控制<br>- MCU程序]

    A --> F[5. 手机App交互<br>App Interaction]
    F --> F1[需要解决的问题<br>- 数据上传<br>- 远程指令<br>- 状态反馈]
    F --> F2[使用器件<br>- ESP8266 WiFi模块<br>- MCU<br>- OLED显示模块(可选)]
```

