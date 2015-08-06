---
layout: post
title:  "Windows下Python安装和pip安装!"
date:   2014-04-08 21:13:00
categories: python
---
#Windows下Python安装和pip安装
- 去官网下载[python-2.7.9.msi](https://www.python.org/downloads/),选择32位的2.7.x的版本的Python并按步骤安装，因为对这个32且2.7.x版本支持的最全面,在安装的时候在安装组件的一步时，勾选pip和 Add python.exe to Path,或者在安装完后将`C:\Python27`加入到PATH路径中，然后一路点“Next”即可完成安装。
- 如果没有安装pip,可以去官网下载[get-pip.py](https://pip.pypa.io/en/stable/installing.html)文件到本地
- `ctrl+R`进入到Windows命令行路径到get-pip.py的存储位置并下面执行`Python get-pip.py`，即可安装

-------
- 无论是Python勾选pip还是由get-pip.py安装pip后一定要将`C:\Python27\Scripts`加入到PATH路径中去，这样才能在Windows命令行下面使用，加入后重启命令行即可使用
- 例如 `pip help`可显示出pip的帮助。