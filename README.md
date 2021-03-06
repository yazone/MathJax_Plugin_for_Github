# MathJax Plugin for Github的下载与安装
基于原项目解决以下问题：无论翻墙安装还是原仓库里本地安装提示：程序包无效。详细信息：“无法加载扩展程序图标“icon16.png”。”。建议直接用第3种方式。


该插件的作用：在网页显示数学公式（由Typora等工具在本地文件编写的Latex公式，上传到github等网站后，md文件中的公式无法正常显示，仍然是Latex代码。在浏览器上安装本插件后，可正常显示部分简单公式。）

不足之处：需要用户安装插件，安装完之后，有的复杂公式仍然无法显示，比如多行公式对齐、方程组等。期待这个插件的更新版本能够解决这些问题，所以这个仓库我没有删除。我目前采用的替代方案是，直接在Typora中将md文件导出为html文件，这时公式本身可以正常显示，然后将html页面部署到github上，并以github pages形式展示。

**1. 谷歌应用商店在线安装**

   打开网页：https://chrome.google.com/webstore/detail/mathjax-plugin-for-github/ioemnmodlmafdkllaclgeombjnmnbima

   点击“添加至Chrome” 

   ![](assets/webstore.png)

   

   出现对话框询问是否添加该插件，点击对话框的“添加扩展程序”按钮

   ![](assets/ask.png)

   

   提示插件已添加到Chrome，则可正常使用了。

   ![](assets/ok.png)


   首选这个方法，如果该网址无法访问，则采用下面第2个方法。

   

**2. 从本仓库下载插件MathJax_Plugin_for_Github_0_2_4_0.crx到本地，离线安装**

   （1）下载本仓库的文件MathJax_Plugin_for_Github_0_2_4_0.crx，保存到本地磁盘。

   （2）在浏览器地址栏输入chrome://extensions

   进入扩展程序页面，启用“开发者模式”

   ![](assets/developer.png)

   （3）用鼠标拖动文件MathJax_Plugin_for_Github_0_2_4_0.crx到浏览器扩展程序页面，出现提示对话框询问是否添加该插件。点击对话框的“添加扩展程序”按钮。

   ![](assets/pull.png)

   

   提示插件已添加到Chrome，则可正常使用了。

   ![](assets/ok2.png)
   
**3. 从本仓库下载local_install下载到本地，离线安装**   
   （1）下载本仓库的文件local_install，保存到本地磁盘。

   （2）在浏览器地址栏输入chrome://extensions
   
   进入扩展程序页面，启用“开发者模式”
   
   “加载已解压的扩展程序”选择“local_install”目录完成安装即可。

   问题分析：程序包无效。详细信息：“无法加载扩展程序图标“icon16.png”。”。crx压缩包里"Icon**.png"为大写，解压出来改成小写就好。
