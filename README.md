Single Device Sensor DataGetter
===

# 项目简介
1. Android 传感器数据采集并写csv文件
2. Android Wear 传感器数据采集并写csv文件

<img src="./imgs/1.png" width=200 height=380 />
<img src="./imgs/2.png" width=200 height=380/>
<img src="./imgs/3.png" width=200 height=380/>

# 相关项目
[Multi-Sensor-DataCollector](https://github.com/LeoCai/Multi-Sensor-DataCollector)
依赖上述项目中的publiclibs项目

# 配置修改
目前暂时只能重编译[Multi-Sensor-DataCollector](https://github.com/LeoCai/Multi-Sensor-DataCollector)中的publiclibs项目，再重新添加依赖

# 项目module介绍
* mobiledata 手机传感器采集
* wear 手表传感器采集
* magnetic 磁力方向据采集
* deletefile 手表数据删除
