# MyRolan
一个快速启动工具。

左侧显示组，右侧显示当前组的项目，点击项目时启动相关程序。
### data.txt 的格式
``` c++
2                                       //组的个数
常用                                     //组名称
3                                       //组下项目的个数
Chrome                                  //项目名称
C:\chrome\chrome.exe                    //程序路径
C:\chrome\chrome.exe                    //图标路径
www.google.com                          //运行参数
QQ
C:\QQ\bin\QQ.exe
C:\QQ\bin\QQ.exe

Everything
C:\everything\everything.exe
C:\everything\everything.exe

网络
1
迅雷
C:\Thunder\thunder.exe
C:\Thunder\thunder.exe
 
```
下一步要做的改进

- 用 json 或 xml 规范化 data 文件的格式