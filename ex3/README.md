1. 找到尽可能多的方法使ex3崩溃

去掉 height 那行 -> 编译错误
height 没有初始值 -> warning 
使用`%f`占位符 -> warning, 打印值错误
使用`%s`占位符 -> warning，运行段错误

2. 执行man 3 printf来阅读其它可用的'%'格式化占位符。如果你在其它语言中使用过它们，应该看着非常熟悉（它们来源于printf）。
>An optional precision, in the form of a period . followed by an optional digit string.  If the digit string is omitted, the precision is taken as zero.  This gives the minimum number of digits to appear for d, i, o, u, x, and X conversions, the number of digits to appear after the decimal-point for a, A, e, E, f, and F conversions, the maximum number of significant digits for g and G conversions, or the maximum number of characters to be printed from a string for s conversions.

3. 将ex3添加到你的Makefile的all列表中。到目前为止，可以使用make clean all来构建你所有的练习。

4. 将ex3添加到你的Makefile的clean列表中。当你需要的时候使用make clean可以删除它。
