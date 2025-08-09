# else-if

执行下面的代码，进行条件判断。

```c
#include <stdio.h>

int main(int argc, char const *argv[])
{
    char c = '6';
    if (c >= 'a' && c <= 'z' || c >= 'A' && c <= 'Z')
	{
		printf("Letter.\n");
	}
	else if (c >= '0' && c <= '9')
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

