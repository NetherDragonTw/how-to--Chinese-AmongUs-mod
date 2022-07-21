# 教你如何汉化 amongus mod

I will update English after Chinese prompt

# 第一步 你要下载mod源代码

你要下载mod源代码，一般在releases里面可以找到。


如果没有 可以用破解c#的dll破解器来搞定

# 第二步 下载dotnet

你要编译源代码 就得下载dotnet。 点击下载[dotnet](https://dotnet.microsoft.com/zh-cn/download/dotnet/6.0)的各种6.0版本。

在[docs.reactor.gg](docs.reactor.gg)文档中，作者使用6.0.1 我比较推荐6.0.4 最新版还是再等等。

# 第三步 下载编辑mod的IDE（编辑器）
这个编辑器 啥都可以 ，例如：
vscode、visit studio 甚至连电脑自带文本编辑器都可以！

# 第四步 汉化源代码 

第四步是十分繁琐的，汉化源代码，顾名思义，你要找到源代码储存身份的位置 

例如 TheOtherRoles 416中 源代码储存在RolesInfo.cs LasMonjas也一样 
（不知道为什么 笔者在编译LasMonjas的过程中出现大量错误，导致无法编译）

# 第五步 编译mod并收尾

结尾啦！ 找到源代码的文件夹 打开cmd 

转到源代码的文件夹的路径 运行两个命令“cd （前面有个空格，输入源代码文件夹路径）”，“dotnet build”

