ubibot-sp1

2019-06-20 11:07:58 孙浩原始程序

2019-06-21 18:59:24 移植代码中， MQTT。。。。。 

2019-07-16 17:49:11 基本移植完成，发现BUG，按键定时器与主函数定时器冲突，导致按键错乱。

2019-07-19 14:58:40 实现网络控制开关、电压电流功率等数据上传云，修复7759B，代码中 0 做除数导致系统复位BUG，实现外接DS18B20读取。

2019-07-23 16:49:33 完成代码移植，功能实现： OTA，外接485读取，外接DS18B20读取，数据上传， DS18B20 读取加入平均滤波功能，规避错误值。

2019-07-24 10:33:10 修改数据上传采用 信号量 方式，增加开关打开，7759b 任务打开，开关关闭，任务挂起。