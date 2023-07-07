1. 寻找其他通过修改printf使这段C代码崩溃的方法。

`printf("You have %s awesome super powers.\n", super_power);` -> warning ，段错误

2. 搜索“printf格式化”，试着使用一些高级的占位符。
```c
printf("You have %5.2f awesome super powers.\n", super_power);
printf("I have a first name %-5s.\n", first_name);
printf("I have a last name %-5s.\n", last_name);
```

3. 研究可以用几种方法打印数字。尝试以八进制或十六进制打印，或者其它你找到的方法。

`%X` 16进制 `%O` 8进制

4. 试着打印空字符串，即""。

`printf("\"\"");`