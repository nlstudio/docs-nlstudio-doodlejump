# 在 Dev-C++ 下编译

本节将介绍在 Dev-C++ IDE 下编译本项目的简要步骤。



## Step 1. 修改编译器选项

在 `工具 - 编译器选项` 中勾选 `在连接器命令行加入以下命令` 并且在下面的文本框中追加 `-lws2_32` 选项即可。

![在顶部工具栏中找到编译选项](img/compiling-guide/devcpp1.png)

![调整编译器选项](img/compiling-guide/devcpp2.png)



## Step 2. 进行编译

仅需打开 `base.cpp` 文件并对其进行编译即可。