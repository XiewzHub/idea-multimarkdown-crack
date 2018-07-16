# 一. 安装multiMarkdown插件
1. 在idea设置中找到插件设置Plugins
2. 添加插件  
    点击browse repositories...，在搜索框中输入markdown navigator找到插件，点击install等待安装成功
# 二. 破解multiMarkdown插件
破解方法很简单 -->
用此项目编译后，将LicenseAgent.class文件替换掉jar包中的class文件
## 这里以我本地的破解为例
1. 对应jar包位置：  
C:\data\java\JetBrains\IntelliJ IDEA 2018.1.5\plugins\idea-multimarkdown\lib
2. 使用压缩软件打开jar包，找到\com\vladsch\idea\multimarkdown\license目录
3. 将已经编译好的class文件拖入，替换掉原来的class文件，**建议先做备份**
4. 如果无法替换，需要先关闭idea软件，因为软件会占用文件，导致无法进行操作，替换成功后再次启动即可
5. 本次破解所改动的地方都加了注释，注明了改动的含义

<font face="楷体" size="5" color="#00ffff">
这里已经将编译好的class文件放入result文件夹中，目前可以直接使用</font>

> 本破解方法仅供参考，如有其它更好的的方法，请告知，多谢多谢