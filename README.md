# DELL-Vostro-5880_OC
机型：Dell Vostro 5880-China HDD Protection

CPU: Intel i5 10400

核显：UHD630

内存：镁光8g*2

硬盘：杂牌256g sata

网卡：219v

声卡：alc256

实现功能：1.CPU睿频 2.主板核显DP、HDMI正常输出 3.音频正常 4.有线网卡正常 5.睡眠正常唤醒 6.USB输出定制

BUG:1.无线蓝牙无解（博通卡已购，到手再折腾）
    
    2.一旦在mac系统点重启，机箱电源不能断电，造成卡死。但关机功能正常。（急需大佬帮助解决）
使用须知：

此OC需用ru.efi解锁cfg、dvmt64M才能正常使用，修改地址分别为：CpuSetup 0x3E值改成0 SaSetup 0xF5值改为2

自行定制三码

玩了几年黑苹果个人第一次完整配置OC，不足之处请多指教。
