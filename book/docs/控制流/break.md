# break

执行下面的代码，在循环中根据指定条件跳出循环。

```c
#include <stdio.h>

int main(int argc, char const *argv[])
{
    int i;
    for (i = 0; i < 10; i++)
    {
        if (i == 6)
        {
            break;
        }
        printf("%d\n", i);
    }
    return 0;
}
```

