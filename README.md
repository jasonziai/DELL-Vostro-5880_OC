# DELL-Vostro-5880_OC
## 配置
机型：Dell Vostro 5880-China HDD Protection

主板：H470 Dell OEM

CPU：Intel i5 10400

核显：UHD630

独显：Nvdia GT710
_（鸡肋，直接拔了）_

内存：Micron 8g*2

硬盘：Netcore 256g SATA

板载网卡：Intel I-219v

板载声卡：Realtek ALC 256

无线网卡：
~~Realtek 8723DE~~
___替换为BCM94352z（为实现第7项功能）___


## 实现功能：

   1.CPU睿频 
   
   2.显存正常，主板DP、HDMI正常输出 
   
   3.音频正常 
   
   4.有线网卡正常 
   
   5.睡眠正常唤醒 
   
   6.USB所有接口定制 
   
   ___7.双向airdrop、随航、通用控制功能正常___

## 已知BUG:

   ~~1.无线蓝牙无解（博通卡已购，到手再折腾）~~ 已安装bcm94352z网卡，网络蓝牙免驱动，无功能缺失。
    
   ~~2.在Mac系统重启，-v跑完码显示器无信号后，机箱电源仍不断电，造成卡死，只能长按电源键强行关机。此故障仅限重启，关机功能正常。（急需大佬帮助解决）~~
   v1.1已打补丁修复。
   
## 使用须知：

1.MacOS安装版本为Ventura 13.0，其他版本未测

2.因戴尔oem主板设置缺失，需用ru.efi解锁cfg、dvmt64M才能正常使用，修改地址分别为：CpuSetup 0x3E值改成00 SaSetup 0xF5值改为02

3.自行定制三码

玩了几年黑苹果个人第一次完整配置OC，不足之处请多指教。
