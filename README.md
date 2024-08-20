# 部署zzj攻击系统的流程

## 写的尽量简单易懂，尽量做到让对计算机不是很熟悉的人也能部署zzj攻击系统，实现人人皆可自由制裁zzj

**考虑到Linux用户比较牛逼，知道大概该怎么做，因此下面以Windows系统为例**



## Step1. 下载`fuckzzj.zip`

根据您的系统类型，选择下载 fuckzzj_x64.zip （64位）或者 fuckzzj_x86.zip （32位）。
如果您不知道您的系统是64位还是32位，请按 win+R 打开运行窗口，输入cmd并回车，在cmd中输入 systeminfo | grep "System Type" 稍等片刻，就会显示出您的系统是64位（x64-based PC）还是32位（x86-based PC）



从百度网盘下载：https://pan.baidu.com/s/1e-BBdN2_ZUiTo-47gW4Wqg?pwd=zzj4 
提取码：zzj4

或者从github下载：https://github.com/Simpidbit/fuckZZJ/releases/tag/fuckzzj

下载后解压，得到`fuckzzj_x64`或者`fuckzzj_x86`文件夹（下面统一称为`fuckzzj`文件夹）。



## Step2. 启动zzj制裁服务

直接双击`fuckzzj`文件夹中的`fuck.bat`即可，会弹出一个黑乎乎的命令行窗口，不要关闭！就这样放着就行



## Step3. 登录QQ

`fuckzzj`文件夹内有`Lagrange.OneBot`文件夹，点进`Lagrange.OneBot`文件夹，一直到最深层有一个`Lagrange.OneBot.exe`，**鼠标右键选择`以管理员身份运行`！！！不然无法正常访问网络**，之后会弹出一个黑乎乎的窗口，稍等一会，这个黑乎乎的窗口中会显示一个二维码，用手机QQ扫描这个二维码，即可授权登录。你用手机QQ扫描二维码的时候登录的是哪个账号，哪个账号就会被机器人附体，手机QQ可以和`Lagrange.OneBot`同时登录，但电脑上的QQ（包括Linux QQ）都不能同时和`Lagrange.OntBot`登录。



## Step4. 完成

至此，您的zzj制裁机器人已经开始运行，不要关闭`Lagrange.OneBot.exe`的那个黑乎乎的窗口，也不要关闭Step 2中的那个黑乎乎的窗口，zzj制裁机器人就会一直运行，zzj每一次发言都会受到制裁。机器人运行期间您也可以在手机上和机器人用同一个号，互不影响



## 补充说明

- 此项目依赖[Lagrange.OneBot](https://lagrangedev.github.io/Lagrange.Doc/Lagrange.OneBot/)

- 为了防止 zzj 修改源码中的目标QQ号，原本的.py文件经过编译成为.pyc文件，.pyc文件不是可以直接编辑的代码文件，可以避免 zzj 修改代码中的QQ号祸害他人。如果需要原本的.py文件，请QQ联系我或者提issue

- 这是第一个版本，由于内置了一个python，因此文件体积较大，我在考虑用C++代替python，C++可以直接编译出可执行文件，安全性更高，且不需要下载多余的工具，单一个.exe文件，点开即用，体积更小，但写出来可能需要一些时间，在C++版本推出之前的迭代都是python实现，文件结构不会有太大变动，更新时只需用最新的.pyc文件替换老的.pyc文件即可
- 如果希望其他含zzj的群或者zzj有其他QQ号，请联系我或者提issue

  目前已经对zzj实施制裁的群：642710446

  目前已经制裁的zzj QQ号：3197769695