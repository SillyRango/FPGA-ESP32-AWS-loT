# FPGA-ESP32-AWS-loT（2020年新工科联盟-Xilinx暑期学校（Summer School）项目）
## 项目简介
- 当下社会，人们的生活质量正在提升，更多人选择在锻炼时记录自己的身体情况、步数等等。他们大多携带手机或者是运动手表，其实主要需求无非就是测量步数。但手机却给锻炼增加了额外的负载，而昂贵的运动手表让我们本就捉襟见肘的钱包雪上加刷。其实你只需要一个便携的搭载esp32芯片的fpga开发板，便能完成数据的测量。相比手机沉重的躯壳，薄如蝉翼的开发板不仅让你轻松甩掉了手机冗余的重量，也将工作中琐碎的消息通知抛在脑后，享受夜跑的愉快轻松。
- *锻炼之余，当朋友们拿出手机和他们的爱人亲密互动时，您不妨拿出Spartan-7 XC7515开发板；因为只有这块集成了现代工业智慧的FPGA，才能给你人生带来真正的快乐。*
## 产品功能
- 本项目使用Spartan-7 XC7S15（Xilinx）开发板，实现通过开发板自带的加速度传感器和陀螺仪 （Accelerometer &Gyroscope）传感器 6-axis LSM6DS3TR，实现摇动步数的采集和上传。无需外设。用户可以在aws IoT 控制台或者PC端MQTT查看实时数据。
## 硬件/软件要求
- FPGA Chip: Spartan-7 XC7515
- WIFI/BLE: ESP32
- vivado2018.3
- ardunio1.8
- MQTT.fx- 1.7.1
## 贡献者
- Silly Rango
- 小罔
