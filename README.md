# 一个简单的单元测试
安装Visual Studio:
1.去下面这个网址下载安装Visual Studio
https://visualstudio.microsoft.com/zh-hans/downloads/
打开Visual Studio Installer选择Community(社区版)的Visual Studio去安装。
feixinyu111/images/1.png
2.在“工作负荷”模块选择自己需要的包，如果这个时候还不知道自己需要什么，等需要的时候再打开“Visual Studio Installer”再下载就行。

3.“单个组件”和“语言包”这样勾选。

4.选择Visual Studio的安装位置，在这一模块，Visual Studio IDE更改文件夹的位置没有什么大问题，重点说下“共享组件、工具和SDK”，有些人这个地方是暗的，不能更改安装位置，如果出现这个问题，去找到电脑上 VS 的注册表，删除共享组件、工具和 SDK 的注册表：
步骤：WIN + R --> regedit --> HKEY_LOCAL_MACHINE -->SOFTWARE -->Microsoft -->VisualStudio --> Setup-->删除 SharedInstallationPath

5.点击安装，Visual Studio就开始安装啦。







一份简单的单元测试：

打开Visual Studio











选择开发语言

选择模板





第一次进入需要配置项目(后面的项目名称变为ClassLibrary3了，是因为我又新建了新的项目，按项目名称为ClassLibrary3来看后面的内容)






对下面一段程序进行单元测试（以C#为例），这里可以观察一下解决方案里面的内容在单元测试之前的状态。

创建单元测试











单击“创建单元测试”之后会出现下面这个页面，点击“确定”。













创建单元测试结束后，我们再次观察解决方案这块的内容，发现这个时候除了原先就有的项目之外，还出现了Test的部分。

在单元测试文件中输入以下代码











选择顶部菜单栏中的“测试”->“测试资源管理器”去运行单元测试。

运行完成后，测试通过。
