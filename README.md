<!--
 * @Description: 
 * @Author: you-know-who-2017
 * @Github: https://github.com/you-know-who-2017
 * @Date: 2019-12-11 21:46:26
 * @LastEditors: you-know-who-2017
 * @LastEditTime: 2019-12-11 21:46:34
 -->
# asmTutor

## DosBox使用方法

```bash
mount c ~/asmTutor
c:
```

挂载相应目录

或者在dosbox的配置文件里默认执行以上命令就可以实现

```bash
masm -> 生成obj文件
link -> 生成exe文件
debug -> 运行分析exe文件
```

### Debug

> u命令（各个命令的作用在文末有详细说明）。对机器代码反汇编显示
> A命令作用：输入汇编指令
> G命令作用：执行汇编指令。
> > G命令的使用方法是：G [=起始地址] [断点地址]，意思是从起始地址开始执行到断点地址。如果不设置断点，则程序一直运行到中止指令才停止。
> U命令作用：对机器代码反汇编显示。
> > U命令的使用方法是：U [范围]。如果范围参数只输入了起始地址，则只对20H个字节的机器代码反汇编。执行命令U100，观看反汇编结果。
> N命令作用：设置文件名，为将刚才编写的汇编程序存盘做准备
> W命令作用：将文件或者特定扇区写入磁盘

