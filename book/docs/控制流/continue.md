# continue

执行下面的代码，在循环中根据指定条件进行下一次循环。

```c
#include <stdio.h>

int main(int argc, char const *argv[])
{
    int i;
    for (i = 0; i < 10; i++)
    {
        if (i == 6)
		{
			continue;
		}
		printf("%d\n", i);
    }
    return 0;
}
```

