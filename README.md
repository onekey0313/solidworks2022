# solidworks2022
## 安装问题描述
问题一：
Solidworks无法获得下列许可Solidworks standard无效的(不一致的)使用许可号码(-8,544,0)

![sw](https://i0.hdslb.com/bfs/article/40f686b76d38d845ea3b0d4849e454fe50fb6161.jpg@942w_632h_progressive.webp)

解决方法：

- ①把SolidSQUAD_下Program Files和Program Files(x86)中所有内容拷贝到系统C盘对应的文件夹中(这一个步骤，在很多安装教程上都没有说)

- ②把此路径下的C:\Program Files\SOLIDWORKS Corp\SOLIDWORKS里的netapi32.dll文件，复制到安装目录的SOLIDWORKS文件夹里即可。 
