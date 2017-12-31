## 输入x,n，求x的n次方
```c
#include<stdio.h>
int f(int x,int n){
	int fac;
	if(n==0)
		fac=1;
	else{
		fac=f(x,n-1)*x;
	}
	return fac;
}
main(){
	int x,n,h;
	scanf("%d%d",&x,&n);
	h=f(x,n);
	printf("%d\n",h);

}
```