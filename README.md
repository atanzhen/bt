BT面板旧版本安装包

都是官方原版下载下来的

测试过7.4.5到7.7.0是可以降级的其他的降级后有问题打不开

降级解除手机绑定的只有这几个版本可以，这几个实测过其他的都不行

LinuxPanel-7.4.5.zip

LinuxPanel-7.4.7.zip

LinuxPanel-7.4.8.zip

LinuxPanel-7.5.1.zip

LinuxPanel-7.5.2.zip

LinuxPanel-7.6.0.zip

LinuxPanel-7.7.0.zip


降级步骤：

1、下载离线包

2、将升级包上传到服务器中的/root目录

3、解压文件：unzip LinuxPanel-x.x.x.zip （x.x.x是版本号，刚才下载哪个就输入哪个）

4、切换到升级包目录：cd panel

5、执行升级脚本：bash update.sh

6、删除升级包：cd .. && rm -f LinuxPanel-7.4.5.zip && rm -rf panel

更多图文教程请访问：https://masuc.cn/39548.html
