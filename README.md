# Lenovo_G400_EFI
Lenovo G400 EFI for Mojave10.14.6

#机型以及配置说明
* 电脑型号    联想 Lenovo G400 20235 笔记本电脑    
* 处理器    英特尔 第三代酷睿 i5-3230M @ 2.60GHz 双核 四线程
* 主板    联想 00000000Not Defined ( Intel HM76 Express 芯片组 )
* 内存    8 GB ( 三星 DDR3L 1600MHz / 记忆科技 DDR3L 1600MHz )
* 主硬盘    西数 WDC WDS120G1G0A-00SS50 ( 120 GB / 固态硬盘 )
* 集成显卡   Intel(R) HD Graphics 4000 (2G显存)
* 核心显卡    AMD Radeon HD 8570M  (2G显存) 
* 声卡    Conexant SmartAudio HD @ 英特尔 Panther Point High Definition Audio Controller
* 有线网卡    鈺硕 QCA8172 Fast Ethernet(Qualcomn Atheros AR8172 PCI-E Fast Ethernet) 
* 无线网卡    Qualcomn Atheros AR9485 Wireless Network Adapter
* 蓝牙       Qualcomn Atheros AR3012 Bluetooth 4.0

#已经实现
1. 核心显卡(已经成功驱动，并已经注入缓冲区补丁，使得从默认的1536M正确显示为2048G)
2. 声卡(已经自动注入为3并成功驱动)
3. 有线网卡(成功驱动)
4. 无线网卡(已经成功驱动，但是需要一些手段)
5. 内存(成功驱动)
6. 亮度调节(已经加入补丁，使得可以使用了)
7. 等待完成

#无法实现
1. 在笔记本上独显无法被驱动(原理性问题)
2. 蓝牙在10.13之后就无法被成功驱动，即使驱动也无法进行关闭和连接操作，所以去掉了该模块

