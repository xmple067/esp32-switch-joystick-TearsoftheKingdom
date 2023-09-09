# esp32-switch-joystick-TearsoftheKingdom
# 塞尔达：王国之泪 ESP32单片机 自动化

# 硬件需求
### Switch主机 * 1
### LOLIN S2 Min * 1
### Switch底座 * 1
### USB线（连接主机与开发板） * 1

# 刷写固件
### 1.下载ZIP源码
### 2.单片机连接电脑 （按住RST，点击0，松开RST,在松开0即可）
### 3.打开刷写固件页面（ESP Web Flasher）
### 4.页面右上角选择 460800 Baud。点击Connect
### 5.弹出的页面选择单片机
### 6.擦除设备 ，等待擦除完成
### 7.选中 firmware\uf2\tinyuf2-lolin_s2_mini-0.16.0 下bin固件。
### 8.写入完成后双击设备上的RST按钮即可
### 9.固件写入完成

# 部署程序
### 1.单片机连接电脑（点击RST，PC识别卷标为CIRCUITPT的U盘）
### 2.删除CIRCUITPT的文件
### 3.拷贝src目录下的所有文件至CIRCUITPT根目录
### 4.部署程序完成
### 5.连接Switch 即可运行


# 目前已有功能
### 盾跳YB复制

# 预计追加功能
### 复制武器
### 复制炸弹花 蜥蜴 鱼
### 复制左纳乌装置
### 火山刷词条

# 注意事项
### 随便一款手机数据线都可以支持，单片机不要直连Switch 请使用底座或OTG转接口，直连无法识别。



特别感谢 
豆汁儿 大佬提供的固件
