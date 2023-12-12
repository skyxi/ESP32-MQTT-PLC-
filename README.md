# ESP32-MQTT-PLC-
ESP32基于MQTT协议PLC数据低成本采集控制方案：
使用esp32作为数据传输，PLC输入点采集现场开关状态和一些模拟量，数据储存在PLC内部，通过ESP32轮询后发送到云端。

需要的硬件：
支持RS485通信的PLC，RS485转TTL模块，ESP32开发板
本项目使用免费EMQX作为mqtt服务器

![无标题](https://github.com/skyxi/ESP32-MQTT-PLC-/assets/22840902/06e7d3da-e471-4cbf-b074-3b6cf37595ec)
