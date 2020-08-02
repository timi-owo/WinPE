【Windows Preinstallation Environment】
简称WinPE，用于在windows部署过程中承载安装程序的迷你操作系统，被我们魔改后用于运行其它程序以进行运维工作。

【WimTool】用于打包和拆包以及挂载.wim文件。

【boot.wim】基于Win10 (10.0.10586)制作的64位PE系统。由于Github上传限制，弄了压缩分卷 boot.zip + boot.z01

【UltraISO】用于修改.iso文件，然后将其写入U盘作为启动引导盘。

【WinPE UEFI + Legacy.iso】用于开机引导进入PE系统的底包，可用UltraISO修改替换\sources\boot.wim。

【Dism++】用于在挂载.wim文件后，向里面添加驱动等。