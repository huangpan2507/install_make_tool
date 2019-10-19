# install_make_tool

1. 第一步，安装 choco工具
这是关于电脑运行make时报错的问题。https://blog.csdn.net/IOT_victor/article/details/89330953   这里面是说下载一个make的包，
然后我进入官网https://chocolatey.org/packages/make， 发现还要安装 choco工具，然后在该网页上找到了 package 这个按钮，点击进去，里面有很多包，第一个就是choco  点击去！ 
点击去后， 看见命令，按提示就好了。 输入 Get-ExecutionPolicy 命令   If it returns Restricted, then run Set-ExecutionPolicy AllSigned or Set-ExecutionPolicy Bypass -Scope Process.
在输入 Set-ExecutionPolicy AllSigned时，提示执行策略更改， 输入yes。
然后再 输入 Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))。根据提示就好，该yes就yes，就自动安装好了choco，  输入 choco测试是否安装成功！

2. 第二步， 安装make
输入  choco install make  即可！


下面是我写的关于解决此问题的博客！
https://blog.csdn.net/weixin_39209112/article/details/102570632


2.发现以上操作并没有解决问题
按如下操作：解决，make等命令问题
https://blog.csdn.net/wolf1132/article/details/88991680
https://blog.csdn.net/weixin_39198406/article/details/82948003
