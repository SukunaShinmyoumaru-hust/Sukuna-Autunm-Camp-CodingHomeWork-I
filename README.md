### Sukuna秋冬令营大作业（I）

#### 任务一

cd到本文件夹。执行下面的命令

```
cd StopWait
mkdir build
cd build
cmake ..
```

尝试修正错误（提示：修改cmakelist.txt）

#### 任务二

修正完错误之后，执行

```
make
```

尝试修正错误。

至此，要写一份实验报告，说明一下C构建系统的用法，尝试理解通过Cmake生成的Makefile文件。命名为report-1.md。


#### 任务三

上网搜索GBN和SR协议，尝试去理解GBN和SR的意义。将停等协议改造成GBN和SR协议。

#### 任务四

基于GBN协议进行修改，修改的内容是，当出现三个冗余ACK的时候，将缓冲区的报文全部重传一遍。

至此，你可以写一份实验报告，阐述一下你的思考。命名为report-2.md。
