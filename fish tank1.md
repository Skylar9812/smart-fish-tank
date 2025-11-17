```mermaid
graph TB

    %% 第一层：功能
    A[Smart Fish Tank System]

    %% ---------------- Oxygenation ----------------
    A --> B[1. Oxygenation]

    %% 第二层：问题
    B --> B1[Problems solved: oxygen timing, remote on/off]

    %% 第三层：器件（每一个独立一个框）
    B --> B2[Relay]
    B --> B3[MCU]
    B --> B4[ESP8266]

    %% ---------------- Heating ----------------
    A --> C[2. Heating]

    %% 第二层：问题
    C --> C1[Problems solved: temperature detection, heating decision, safety]

    %% 第三层：器件（每一个独立一个框）
    C --> C2[DS18B20 Sensor]
    C --> C3[Relay]
    C --> C4[MCU]
    C --> C5[Power Module]
```
