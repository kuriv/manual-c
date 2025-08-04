# else-if

执行下面的代码，进行条件判断。

```c
#include <stdio.h>

int main(int argc, char const *argv[])
{
    char a = '6';
    if (a >= 'a' && a <= 'z' || a >= 'A' && a <= 'Z')
	{
		printf("Letter.\n");
	}
	else if (a >= '0' && a <= '9')
	{
		printf("Number.\n");
	}
	else
	{
		printf("Other.\n");
	}
    return 0;
}
```

