# MinerU-OneClick

<img width="1336" height="939" alt="image" src="https://github.com/user-attachments/assets/4b6aaa53-f275-46bd-bb6b-9c8a648d74a9" />


MinerU是一款非常热门的高质量的PDF转Markdown和JSON格式软件，当前更新到了2.5.4版本，为了方便大家快速上手体验，省去安装部署耗时，我制作了最新版免安装一键启动整合包，下载解压即用。

*2025年2月21日制作了v1.1.0版整合包

*2025年2月27日制作了V1.2.0版整合包

*2025-10-24 更新2.5.4版本

## MinerU整合包使用说明

首先将软件压缩包从网盘下载到本地电脑上并解压。

然后双击运行【启动软件.bat】，稍后即可自动打开WEBUI操作界面。

首先选择待处理PDF文件，你可以点击选择文件按钮选择文件，也可以把想要处理的文件鼠标左键按住拖动到软件窗口中。软件也支持批量处理，直接输入文件夹路径即可。软件只支持识别PDF文档和图片格式文件

解析后端：默认pipeline后端，英伟达显卡显存8G以上用户可选择vlm-transformers

解析方法：默认auto模式,你也可以手动选择ocr或txt，如果是纯文本文档，建议选择txt，速度更快

PDF语言：指定文档语言（可提高OCR准确性，仅适用于pipeline后端），填写语言代码，如英语文档填：en，其它语言代码如下：[ch|ch_server|ch_lite|en|korean|japan|chinese_cht|ta|te|ka|th|el|latin|arabic|east_slavic|cyrillic|devanagari]，不熟悉可忽略。

起始页：想从PDF哪页开始处理。页数从0开始计数的，比如想从第二页开始处理，这里就填1

结束页：想要软件处理到哪页结束，和上面一样，填数字

默认只需要设置待处理文件和保存位置即可，其它不需要设置。

表格识别和公式识别功能默认都是开启的，如果你用不到这些功能或是电脑带不动，你可以选择关闭这些功能。

视频教程：https://www.youtube.com/watch?v=6pZfVE0Ui94

## 注意事项

程序要求硬件为图灵架构或更高显卡，建议英伟达显卡为20X或更高系列用户使用

支持英伟达50系列显卡

整合包只支持Windows 10或11系统

软件运行路径中不要有非英文字符和空格，待处理文件同样注意

保存位置不要选择盘符根目录下

## MinerU 2.5.4版一键启动整合包下载链接

https://pan.quark.cn/s/03c6d214394b

## 在线一键启动版

[点击使用云镜像>>](https://www.compshare.cn/images/mF3Ss4b6aV24?referral_code=FlfHWpg22A9EnXni6kYKRv&ytag=GPU_yy_aidayang1024)

## MinerU项目链接

https://github.com/opendatalab/MinerU
