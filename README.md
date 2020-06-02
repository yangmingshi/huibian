《汇编语言》（第三版）清华大学出版社 王爽著 编程代码
一、准备工作：
    1.打开 www.dosbox.com ，下载DOSBox的安装包，安装位置不限
    2.在非系统盘中，新建一个文件夹，文件名中不得出现中文字符。假设在D盘新建的文件夹名称为huibian
    3.运行DOSBox，出现两个窗口，后面的窗口名称为 DOSBox Status Window，按文件路径打开DOSBox的配置文件：dosbox-0.74.conf（数字可能因文件版本不同）
    4.在该文件的末尾加上如下代码：
          mount c: d:\huibian
          c:
      经过以上的一番操作后，PC的D盘huibian文件夹被映射为dos下的C盘
 
