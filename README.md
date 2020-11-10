# makefsfile
  * 1.首先将网页源文件编写好，如工程中webpage文件夹下的文件。
  * 2.将makefsfile工具和webpage放在同一个文件夹下如web.
  * 3.运行cmd,进入到makefsfile工具的目录web。
  * 4.使用makefsfile -i webpage -o fsdata.c -r -h 命令生成一个 fsdata.c文件
  * 5.用#include "fsdata.c"包含进工程
  * 6.主要适用于单片机等内存较小的机器里面创建网页文件。
