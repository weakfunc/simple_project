## 参考资料

ESP32核心板参考：[ESP32S3SuperMini 入门](https://www.nologo.tech/product/esp32/esp32s3supermini/esp32S3SuperMini.html)

ESP32-1.28LCD:[ESP32-S3显示屏开发板1.28寸圆形LCD显示屏 IPS圆形屏GC9A01A QMI8658A 斑梨教程资料程序代码PDF手册](https://spotpear.cn/index/study/detail/id/1315.html)

ESP32获取RSSI：[【玩转ESP32】16、esp32获取rssi，辅助判断硬件是否异常_esp32h2怎么获取rssi-CSDN博客](https://blog.csdn.net/freemote/article/details/118609960)

## 机械设计

IPS屏厚1.5+PCB厚1.6+铜柱高5.3（锂电池厚5+元器件高3）=11.1

底板厚1.9。整体厚度13

## RSSI信号强度测试

测试时间：2024/12/11 5：19

测试环境：室内，无人，环境干扰少。ESP32与AP在基本同一高度，有遮挡。

硬件设备：ESP32S3FH4R2（ESP32S3-SuperMini开发板）

AP基站：手机WIFI热点，手机接入校园网

数据反馈频率：3000ms

| 距离（m） | RSSI值 | 频率 | 备注                                                         |
| --------- | ------ | ---- | ------------------------------------------------------------ |
| 0         | -14    |      | ![](D:\Pro_master\a\hy\img\Snipaste_2024-12-11_05-50-19.png) |
|           |        |      |                                                              |
|           |        |      |                                                              |

