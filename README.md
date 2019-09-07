# shell脚本
## 1. 什么是 shell
- 1.1 shell是一个用c语言编写的程序，是用户使用linux的桥梁；
- 1.2 shell既是一种命令语言，又是一种程序设计语言；
- 1.3 shell是一种应用程序，用户通过该程序界面访问linux内核；
## 2. 什么是shell脚本
- 2.1 shell脚本是为shell编写的脚本程序，后缀为`.sh`;业界所说的shell通常指s`hell脚本`
## 3. shell环境
- 3.1 shell编程跟java编程一样，只需要编辑器和解释脚本的解释器就行了；
shell的解释器众多，常见如下：sh，bash，zsh；
- 3.2 在shell脚本中，`#!`后边的路径所指的程序就是解释此脚本文件的shell解释器；指定 sh 解释器 `#!/bin/sh`;指定bash解释器`#!/bin/bash`
- 3.3  查看支持的shell `cat /etc/shells`
- 3.4 查看shell的帮助信息
    ```
    man bash  查看bash的命令帮助
    info bash 查看bash的信息
    ```
## 4. echo
- echo指代输出命令
- -e 支持反斜杠的控制字符
    ```
    \n 换行符
    \r 回车
    \t 制表
    ```

