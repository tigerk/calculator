# calculator
使用flex，bison实现计算器

> 提前安装flex、bison
```
bison -dv calculator.y
flex calculator.l

- 使用c编译器编译
cc -o calculator calculator.tab.c lex.yy.c

- 执行
./calculator 来输入算式
```
