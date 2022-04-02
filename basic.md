# tang
test during college


#include<stdio.h>
//std-标准 standard input output

int main()//主函数-程序的入口-main函数有且只有一个
//int 是整形的意思
//main前面的int表示main函数调用返回一个整型值

//函数-print function-printf-打印函数

//库函数是C语言本身提供给我们使用的函数
// 这是别人的东西需要访问就需要<>，尖括号内就是访问的文件
//#include
{
	char a = 'S';
	int age = 20;
	long num = 100;
	float f = 5.0;
	double d = 3.14;
	//计算两个数的和
	int he = 0;
	int x = 1;
	int y = 2;
	int sum = 0;
	sum = x + y;
	int num1 = 0;
	int num2 = 0;
	scanf_s("%d%d", &num1, &num2);//&取地址符号
	he = num1 + num2;

	printf("实验\n");
	printf ("%c\n",a);//%c打印字符格式的数据
	printf("%d\n", age);
	printf("%d\n", num);
	printf("%f\n", f);
	printf("%lf\n", d);
	printf("%d\n", sum);
	printf("he=%d\n", he);
	//printf("%f\n", d);也可以，但是上述更精确
	
	return 0;//返回
	//void main 可以但是这是种过时的写法
	// \n有换行的作用
	// 可以用printf("%d\n",sizeof(int));来调查字节个数
	//scanf有自己输入的作用
}
/*
#include <stdio.h>//#include<stdio.h>是在程序编译之前要处理的内容，称为编译预处理命令
#include <string.h>//包含字符串处理函数的头文件
int main() {

	int num1 = 0;
	int num2 = 0;
	int sum = 0;
	char a1[] = "abc";//默认有一个0，0 为结束符号
	char a2[] = { 'a','b','c' ,'0','a',0};//需要手动加上一个0

	printf("%d\n", strlen("c:\test\32\test.c"));
	printf("%c\n", '\32');
	printf("%c\n", '\x61'); 

	printf("%s\n", a1);
	printf("%s\n", a2);

	printf("%d\n", strlen(a1));
	printf("%d\n", strlen(a2));//strlen用于计算数组的长度的,0只是结束标志不会进入长度的计算

	scanf("%d%d",&num1,&num2);
	sum = num1 + num2;
	printf("sum =%d\n", sum);
	sum = 12;
	printf("sum=%d\n", sum);
	printf("as\\tabc");
	return 0;
}
	/* 
\n是换行
\t是水平制表符
\是转义符号
如果要打印\t不应该printf（"\t"）这样只会打印出一堆空格
应该这样输出printf（"\\t"）这样就会打印出\t
\ddd，ddd表示1—3个8进制的数字
\xdd，dd表示2个十六进制数字
	*/
*/
