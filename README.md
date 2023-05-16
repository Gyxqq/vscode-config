# vscode-config
vscode配置
# step1 安装
 下载VScode[链接](https://code.visualstudio.com/)  
 安装vscode
# step 2 安装中文拓展
## 选择拓展  
![](https://github.com/Gyxqq/vscode-config/blob/main/src/image.png)
## 搜索Chinese，选择简体中文安装即可  
![](https://github.com/Gyxqq/vscode-config/blob/main/src/1.png)
# step3 安装c++拓展
## 拓展市场搜索c++
![](https://github.com/Gyxqq/vscode-config/blob/main/src/2.png)
#  step4 下载mingw64工具链
[官网链接](https://www.mingw-w64.org/downloads/)  
[下载链接1](https://github.com/niXman/mingw-builds-binaries/releases)  
[下载链接2](https://github.com/Gyxqq/vscode-config/releases/tag/v1)  
下载链接2中两个文件随机选择一个下载即可
下载并解压文件
# step5 配置环境变量  
[教程](https://blog.csdn.net/wangpaiblog/article/details/113532591)  
## 将解压出来的文件的bin文件夹的路径添加到环境变量
以x86_64的压缩包为例
![](https://github.com/Gyxqq/vscode-config/blob/main/src/3.png)
![](https://github.com/Gyxqq/vscode-config/blob/main/src/4.png)
# step6 配置vscode拓展
## vscode设置里面搜索include，找到下面这两项，点击添加
![](https://github.com/Gyxqq/vscode-config/blob/main/src/5.png)
添加刚刚解压的mingw64工具链的文件夹路径再加上**  
如
```
D:\edgedownloads\Compressed\x86_64-8.1.0-release-posix-seh-rt_v6-rev0\mingw64\**
```
配置结束
