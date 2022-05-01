# 安装并配置Windows Terminal
效果：
![](https://s1.ax1x.com/2022/05/01/O9Dorj.png)
# SSH练习
我选择将自己的ubuntu虚拟机作为服务器。先启动ssh服务,并修改配置文件：
![](https://s1.ax1x.com/2022/05/01/O9rVzD.png)
![](https://s1.ax1x.com/2022/05/01/O9sPXQ.png)
密钥（生成密钥时候忘截图了）

![](https://s1.ax1x.com/2022/05/01/O9rQot.png)

用scp命令将私钥传到windows上：(D盘)
```powershell
scp username@xxx.xxx.xxx.xxx:~/.ssh/id_rsa D:
```
还需要改变一下windows上id_rsa的权限，否则会提示私钥不够安全，被ignore：

![](https://s1.ax1x.com/2022/05/01/O9rcy4.png)

之后就可以直接用密钥登陆了。

![](https://s1.ax1x.com/2022/05/01/O9sGA1.png)

# git

这里用了第一次的截图。

![](https://s1.ax1x.com/2022/05/01/O9sg9f.png)