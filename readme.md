#   使用说明！！！
一、bios修改建议（以下仅为我自己的改动，跑不进系统看opencore的官网找bios设置建议）
先按 右ctrl+右shift+左alt+f2进入更多菜单
Security
    Trusted Computing
        Security Device Support (disable
    Security Boot
        Security Boot Support (disable 
        
Boot
    Fast Boot (disable 
    
Advanced
    SATA Mode Selection (AHCI
    Software Guard Extensions(SGX) (disable 
    System Agent (SA) Configuration
        Above 4GB MMIO BIOS assignment(enable)
    power&performance-cpu power management control-CPU lock configuration
        CFG Lock(disable 
二、使用前选择好自己想要的版本，两版本说明见2023-9-20更新说明中的新增特点
若要使用apple_music版本需要用iMac pro1,1机型生成序列号等信息
若要使用hevc版本需要用MacBookPro16,1机型生成系列号等信息
三、一定要生成新的序列号等信息！不然进不去系统！

#   2023-9-20更新说明
一、更新内容
又双叒叕重新定制了usb，建议下载后如果不能用也自行定制一下usb
摄像头正常工作
蓝牙正常工作（13.4.1）（还是没有钱买新的免驱网卡，什么时候能有钱啊！！！！）
二、新增特点
apple_music文件夹下的efi可以使用Apple Music无损音乐和杜比全景声(但不支持hevc硬解，支持h.264硬解)
hevc文件夹下的efi支持hevc硬解和h.264硬解（但是不支持Apple Music无损音乐和杜比全景声，不用无损音质的话倒是能用）
三、已知问题
本次仅仅为oc和驱动更新以及对硬解进行支持，并没有在更新的系统上运行，用的系统版本还是13.4.1，新系统不确定能用
蓝牙不能连接除了apple的耳机以外的东西
不支持隔空投送

#   2023-7-20更新说明
一、更新内容
重新定制了usb，解决左侧两个接口无法使用usb3.0的问题
可将系统更新至Ventura 13.4.1(oc0.9.3)
解决了apple music不能播放无损、杜比全景声的问题（需按照建议生成iMac pro1,1的三码）
二、已知问题
原装网卡不能驱动蓝牙，但是旧版macos Ventura13.0.1是可以正常使用的，升级就不能用了，懒得解决了，已经在物色免驱卡了
右侧type-c不能热插拔，不能用usb2.0


