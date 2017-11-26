# Java学习笔记

## 新数据类型
+ byte  -2^7~2^7-1
+ short  -2^15~2^15-1
+ int  -2^31~2^31-1
+ long  -2^63~2^63-1  后缀一定要加L
+ float  8位有效数字  后缀一定要加F
+ double  16位有效数字   后缀可选加D
+ 低精度可以直接赋值给高精度，反之必须使用类型转换运算
+ 对整数使用(char)强制类型转换，数字会变成对应的unicode码对应的字符
+ 数据类型的最大值类似 Integer.MAX_VALUE, 最小值 Integer.MIN_VALUE
## 输入输出数据
+ Scanner 类
+ System.out.print
+ System.out.println  会换行
+ %d
+ %c
+ %f
+ %s
+ %md
+ %m.nd
+ 输入格式类似 C 的printf
## 数组
+ int [] a
+ int a[][]
+ int [] a,b[]  声明了一个一维数组和二维数组
+ 不能直接在中括号内声明数组的长度，使用new声明才可以
+ 与 c 相同，输出char型数组的数组名会输出整个数组的值
## 运算
+ 补码，负数的补码为正数的原码取反后加一
+ 按位与 &
+ 按位或 |
+ 按位非 ~
+ 按位异或 ^
+ a instanceof b b是否是a的祖先
## 面向对象
+ 封装性
+ 继承
+ 多态
+ 成员变量有默认值，局部变量没有
+ 类内变量赋值只能出现在方法体内或在声明的时候赋值
+ UML图
+ 构造方法 类C
+ 类内定义了构造方法，默认构造函数会被覆盖掉
+ 引用类型数据存在栈中，非引用类型数据存在堆中
+ 没有析构函数
+ System.gc() 立即进行垃圾回收
+ 可变对象
+ 关联关系  a类成员变量是b类对象
+ 依赖对象  a类的方法中的参数是b类对象或者方法返回的值是b类对象
+ 实例变量，类变量（static静态变量）
+ 类方法只能由对象调用，只能调用类变量
+ 包名，类似于命名空间，防止变量污染  使用pakeage定义包名
+ import 用于导入别的包里的类
+ java.lang 基本语言类
+ java.io 输入输出类
+ java.util 实用类
+ java.sql 操作数据库的类
+ java.net 实现网络功能的类
+ * 引入全部类
+ private 友好 protected public



