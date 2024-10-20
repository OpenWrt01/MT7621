# MT7621



# #### 安装方法 ######

>>>>>> 方法： 进入后台管理界面
首先在 https://github.com/OpenWrt01/MT7621/tree/main/package 选择下载要在安装的插件压缩包，
下载完后解压缩到硬盘，然后就可以到路由器后台上传插件升级了
	202408_ssr+.zip  ShadowSocksR Plus+ 设置最简单，易用，不需要繁琐的插件支持自动节点切换，有说明文档 
	202408_passwall.zip
	202408_passwall2.zip


进入路由后台操作步骤如下：
1. 点击菜单：应用 -> 软件包 -> 上传软件包 
	把所有 .ipk 文件上传， 上传后自动保存到 /tmp/ipkgs 目录下

2. 点击菜单：应用 -> TTY终端， 
	输入登录用户名，密码 (默认 root 密码 admin)
	执行下面指令，等待执行完成即可， 注意：如果安装的插件比较大，可能需要的等待4-5分钟才能安装完成
	 
	opkg --force-depends install /tmp/ipkgs/*.ipk


命令提示行提示安装好之后就可以菜单里面看到安装好的插件菜单
	OpenWrt原生功能 -> 服务



# >>>>>>  目录optional 下面的为可选安装插件，可以不用装


