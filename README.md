# simulation-init.d


从某些方面讲，这个项目大概算是[360f4复活大法][3mptros]的附属项目

这个项目提供的脚本可能是一个世界上兼容性最差，速度最慢的模拟 init.d 行为的脚本  
甚至要让脚本正常工作的话好像还要安装 [busybox][meefikbusybox]

注意：
如果你的设备安装了 [Magisk][topjohnwuMagisk] ，你应该不需要这个脚本，也不要使用这个脚本，因为 [Magisk][topjohnwuMagisk] 有类似功能  
如果希望脚本正常工作的话最好安装 [busybox][meefikbusybox] ，否则我也不知道会发生什么  

免责：
使用这个脚本出现任何意外我都不负责的……  
虽然我会尽力帮你解决产生的


****
	
安装脚本的步骤：
1. 下载脚本
2. 把脚本复制到任意位置并添加可执行权限
3. 安装并打开 [终端][zt515Ansole]
4. 复制脚本的路径并粘贴在 [终端][zt515Ansole]
5. 使用参数 `-h` 执行一次之后你就知道应该怎么做了，也可以直接使用 `-i` 参数完成安装
6. 按照提示检查脚本是否安装成功
7. 成功后就开始享受 init.d 的便利吧，如果出现问题请向我反馈

*******************
[3mptros]:https://github.com/funnypro/360f4
[meefikbusybox]:https://github.com/meefik/busybox
[topjohnwuMagisk]:https://github.com/topjohnwu/MagiskManager
[zt515Ansole]:https://github.com/zt515/Ansole