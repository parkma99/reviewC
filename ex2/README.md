1. 创建目标all:ex1，可以以单个命令make构建ex1。

2. 阅读man make来了解关于如何执行它的更多信息。
> The purpose of the make utility is to determine automatically which pieces of a large program need to be recompiled, and issue the commands to recompile them. 
>
> The make program uses the makefile data base and the last-modification times of the files to decide which of the files need to be updated.  For each of those files, it issues the commands recorded in the data base.
>
> make executes commands in the makefile to update one or more target names, where name is typically a program.

3. 阅读man cc来了解关于-Wall和-g行为的更多信息。
> Control debug information output.  Note that Clang debug information works best at -O0.  When more than one option starting with -g is specified, the last one wins:-g Generate debug information.

4. 在互联网上搜索Makefile文件，看看你是否能改进你的文件。

5. 在另一个C语言项目中找到Makefile文件，并且尝试理解它做了什么。

