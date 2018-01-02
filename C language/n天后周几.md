## 假设今天周日，n天后周几。
```c
#include<stdio.h>
main(){
	int num;
	scanf("%d",&num);
	switch(num%7){
		case 1:printf("星期一\n");
			break;
		case 2:printf("星期二\n");
			break;
		case 3:printf("星期三\n");
			break;
		case 4:printf("星期四\n");
			break;
		case 5:printf("星期五\n");
			break;
		case 6:printf("星期六\n");
			break;
		default:printf("星期日\n");

	}
}
```