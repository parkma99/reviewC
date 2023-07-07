1. 在你的文本编辑器中打开ex1文件，随机修改或删除一部分，之后运行它看看发生了什么。
> zsh: exec format error: ./ex1

2. 再多打印5行文本或者其它比"Hello world."更复杂的东西。

```c
#include <stdio.h>
int main(int argc, char *argv[])
{
    puts("Hello world.");
    puts("1");
    puts("2");
    puts("sss");
    puts("ads");
    puts("213");

    return 0;
}
```

3. 执行man 3 puts来阅读这个函数和其它函数的文档。

```c
#include <stdio.h>

     int
     fputs(const char *restrict s, FILE *restrict stream);

     int
     puts(const char *s);
```

> DESCRIPTION
>
> The function fputs() writes the string pointed to by s to the stream pointed to by stream.
> The function puts() writes the string s, and a terminating newline character, to the stream stdout.

