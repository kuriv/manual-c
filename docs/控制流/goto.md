# goto

执行下面的代码，在循环中根据指定条件跳转至标记位置。注意，大多数情况下使用 `goto` 语句将造成程序难以理解和维护。

```c
#include <stdio.h>

int main(int argc, char const *argv[])
{
    int i;
    for (i = 1; i < 10; i++)
    {
        if (i == 6)
        {
            goto found;
        }
        printf("%d\n", i);
    }
    return 0;

    found: printf("Found %d.\n", i);
}
```

