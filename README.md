# install_make_tool
这是关于电脑运行make时报错的问题。https://blog.csdn.net/IOT_victor/article/details/89330953这里面是说下载一个make的包，
然后我进入官网https://chocolatey.org/packages/make， 发现还要安装 choco工具，
Run Get-ExecutionPolicy. If it returns Restricted, then run Set-ExecutionPolicy AllSigned or Set-ExecutionPolicy Bypass -Scope Process.
然后安装choco，再用choco安装make即可。
