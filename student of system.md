# 学生系统
## 编写主函数
#include<stdio.h>
void main(){
  void name(char a[],char b[]);
  printf("欢迎来到学生系统\n");
  printf("姓名   年龄  ");
  printf("请输入学生姓名");
}
void name(char a[],char b[]){
  int i = 0;
  while(b[i]!='\0'){
    a[i]=b[i];
    i++;
  }
  a[i]='\0';//将b输入的字符赋值给a
}









##### 需求
1. 需要一个主函数
2. 需要其他函数
3. 需要引用其他函数
4. 调用学生姓名，年龄，住址
5. 主函数有输入函数，且会保存数据
6. 是否跨文件？
