
计算器
======
这是一个用 **C语言** 编写的命令行计算器，支持**数学常量**，**数学函数**和一些**命令操作**。


运算符
------
|  运算符  | 运算操作 | 优先级  |
| :---: | :--: | :--: |
| (   ) | ———— |  1   |
|   ^   | 幂运算  |  2   |
|   %   | 取模运算 |  3   |
|   *   | 乘法运算 |  3   |
|   /   | 除法运算 |  3   |
|   +   | 加法运算 |  4   |
|   -   | 减法运算 |  4   |


数学常量
--------
- `pi` 圆周率
- `Ans` 上一个表达式的结果 初始值为0


数学函数
--------
- `ln(x)` 自然对数值 **(x>0)**
- `abs(x)` 绝对值
- `exp(x)` 自然常数e为底的指数函数值
- `ceil(x)` 向上取整值
- `floor(x)` 向下取整值
- `sin(x)` 正弦函数
- `cos(x)` 余弦函数
- `tan(x)` 正切函数
- `arcsin(x)` 反正弦函数 **(-1<=x<=1)**
- `arccos(x)` 反余弦函数 **(-1<=x<=1)**
- `arctan(x)` 反正弦函数


命令操作
--------
- `cls` 清屏
- `help` 帮助
- `quit` 退出
- `color` 更换控制台颜色


注意事项
--------
1. 计算式中**不能省略紧靠在括号右边的乘号**
2. 你可以使用形如`1.25e6`的**指数形式**来表示数字
3. 计算式的结果的精度最高只能达到****6位有效数字****
4. 计算式必须使用**全英文字符**，所有数学函数和数学常量**不区分大小写**
5. 你可以使用方向键‘上’、‘下’来调用输入并计算过的式子，就像普通的命令行操作那样

***

[Github-Calculator](https://github.com/king2023796417/Calculator) **.King**
