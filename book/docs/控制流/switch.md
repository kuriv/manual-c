# switch

执行下面的代码，进行多路判定。

```c
#include <stdio.h>

int main(int argc, char const *argv[])
{
    char c = '6';
    switch (c)
    {
    	case 'a':
    		printf("Letter a.\n");
    		break;
		case '6':
    		printf("Number 6.\n");
    		break;
		case 'c':
    		printf("Letter c.\n");
    		break;
    	default:
    		printf("Other.\n");;
    		break;
	}
    return 0;
}
```

