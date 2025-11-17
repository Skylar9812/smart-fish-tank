```mermaid
graph TB

    %% 统一浅蓝色样式
    classDef blue fill:#e8f1ff,stroke:#3c6df0,stroke-width:1.4px,color:#1d2d50;

    %% 顶层
    A[Smart Fish Tank System]:::blue

    %% ---------------- Water Quality ----------------
    A --> D[3. Water Quality Monitoring]:::blue

    D --> D1[Problems solved:<br>• TDS detection<br>• threshold check<br>• warning]:::blue
    D --> D2[TDS Sensor]:::blue
    D --> D3[LED Indicator]:::blue
    D --> D4[MCU]:::blue
    D --> D5[ESP8266]:::blue

    %% ---------------- RGB Lighting ----------------
    A --> E[4. RGB Lighting]:::blue

    E --> E1[Problems solved:<br>• color mixing<br>• brightness control<br>• mode switching]:::blue
    E --> E2[RGB LED]:::blue
    E --> E3[Resistors]:::blue
    E --> E4[GPIO Pins]:::blue
    E --> E5[MCU]:::blue

    %% ---------------- App Interaction ----------------
    A --> F[5. App Interaction]:::blue

    F --> F1[Problems solved:<br>• data upload<br>• remote commands<br>• status feedback]:::blue
    F --> F2[ESP8266]:::blue
    F --> F3[MCU]:::blue
    F --> F4[OLED Display optional]:::blue
