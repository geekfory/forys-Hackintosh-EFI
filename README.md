# forys-Hackintosh-EFI

我自己的黑苹果efi，我的电脑配置如下：

	处理器          英特尔 Xeon(至强) E3-1231 v3 @ 3.40GHz 四核
	主板            技嘉 B85M-D3H v1.0 ( Lynx Point )
	显卡            Nvidia Quadro K620 ( 2 GB / Nvidia )
	内存            16 GB ( 威刚 DDR3 1600MHz )
	声卡1           瑞昱 ALC892 @ 英特尔 Lynx Point HD Audio Controller
	声卡2           Nvidia nForce2 ISA Bridge @ Nvidia High Definition Audio Controller
	网卡            瑞昱 RTL8168/8111/8112 Gigabit Ethernet Controller / 技嘉
	无线网卡1       瑞昱 RTL8188CUS 802.11n WLAN
	无线网卡2       瑞昱 802.11ac NIC

-------------------------------------
文件说明：
	
	10.11.2 EFI.part1.rar 
	10.11.2 EFI.part2.rar ------- MAC 10.11.2 的EFI文件，分卷压缩（旧版备份）


	10.13.6(17G65) - EFI (B85M-D3H E3-1231-V3 K620).part1.rar 
	10.13.6(17G65) - EFI (B85M-D3H E3-1231-V3 K620).part2.rar ------- 10.13.6(17G65)的EFI文件（分卷压缩）。由于N卡只能支持到这个版本，如果我不换电脑或者显卡的话应该会一直用下去了。
	
	
	10.13.6(17G65) - Udisk_EFI.zip ------- 10.13.6(17G65) clover U盘安装版EFI文件
	
	
	CUDA+NVDIA+声卡补丁.rar ------- 如名所示
	
	
	e3-1321v3-asus-b85m-gaming-giga-1060-g1-hackintosh-master.zip ------- 我调EFI时候的参考文件（直接用这个的话声卡失效）
	
	
	RTLWlanU_MacOS10.9_MacOS10.13_Driver_1830.20.b13_1827.4.b29_UI_5.0.6.b9.zip ------- 无线网卡驱动

	
	时间同步.reg ------- 同步win和mac的时间，但是BIOS时间会慢8小时

-------------------------------------
免责声明：
此项目仅用于个人文件备份，因使用此项目文件造成的任何问题本人概不负责。
