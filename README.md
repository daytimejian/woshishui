#include<stdio.h>//包含一个叫stdio.h的文件
//std-标准standard input output
/*int main(void)//主函数-程序的入口-main有且只有一个
//int是整型的意思
//main前面的int表示main函数调用返回一个整型值
{
	printf("hello word\n");
	//这里完成任务
	//在屏幕上输入hello word
	//函数-print function-printf-打印函数
	//\n是换行的意思
	//库函数-c语言本身个我们提供的函数
	//别人的东西-打招呼-#include

	return 0;//返回 0
}*/
//char-字符类型
/*int main()
{
	//char ch='A';//内存
	//printf("%c\n",ch);//%c-打印字符格式的数据
	//int age = 20;
	//printf("%d", age);//%d打印一个十进制数据
	//short int -短整型
	//long 长整型
	//%f-打印浮点数字-打小数
	//%p-以地址的形式进行打印
	//……
	//float f = 5.0;
	//printf("%f", f);
	double d = 3.14;
	printf("%lf\n", d);
	return 0;
}*/
/*int main()
{
	printf("%d\n", sizeof(char));//1
	printf("%d\n", sizeof(short));//2
	printf("%d\n", sizeof(int));//4
	printf("%d\n", sizeof(long));//4
	printf("%d\n", sizeof(long long));//8
	printf("%d\n", sizeof(float));//4
	printf("%d\n", sizeof(double));//8

	short int age = 20;//2 2^16-1=65535
}*/
/*int main()
{
	short age = 20;//向内存申请2个字节=16bit位，用来存放20
	float weight = 95.6f;//向内存申请四个字节存放小数
	return 0;
}*/
/*int num2 = 20;//全局变量-定义在代码块之外的变量
int main()


{
	int mum1 = 10;//局部变量-定义在代码块内部的变量
}*/
//int a = 100;//局部变量和全局变量的名字建议不要相同-容易误会，产生bug
//当局部变量和全局变量名字相同时，局部变量优先
/*int main()
{
	int a = 10;
	printf("%d\n", a);

	return 0;
}*/
/*int main()
{
	//计算两个数
	int num1 = 0;
	int num2 = 0;
	//输入函数使用-输入函数scanf_s
	scanf_s("%d%d",&num1,&num2);//取地址符号&
	int sum = 0;//c语法规定，变量要定义在代码块前面
	sum = num1 + num2;
	printf("sum=%d\n", sum);

	return 0;
}*/
/*int main()
{
	//局部变量的作用域
	{
		int num = 3;
		printf("num%d=\n", num);
	}
	return 0;
}*/
//int global = 2022;

/*int main()
{
	printf("%d", global);

	return 0;
}
void test()
{
	printf("test()--%d\n", global);
}*///全局变量是整个工程
/*int main()
{
	//未声明标识符
	//声明
	extern int g_val=2021;
	printf("g_val=%d", g_val);

	return 0;
}*/	/*int main()
{
	{int a = 10;
	printf("%d\n", a);//ok
	 }
	printf("a=%d\n", a);//error

		return 0;
}*/
