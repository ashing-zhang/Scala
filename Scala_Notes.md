1.字段/变量的定义Scala中使用 **var/val 变量/不变量名称：类型** 的方式进行定义。其中var和val的区别在于，var是变量，以后的值还可以改变，val的值只能在声明的时候赋值，但是val不是常量，只能说是不变量或者只读变量。

2.类型推断：

```
能让scala自动理解省略的类型。
```

3.尽可能才用val的不变量。

4.scala没有基本数据类型的概念。

5.scala表达式

```
不使用return语句，最后一个表达式即返回值。
```

6.scala块表达式

```
--块中最后一个表达式的值就是块的值。
--表达式语句既可以用分号分隔，也可以用换行来分隔。
```

7.to和until

```
to:包含尾部
until：不包含尾部
```

8.用idea maven创建scala工程

```
1.创建maven工程
2.依赖文件要添加对scala-library的依赖
3.创建名为"scala"的文件夹
4.右击"scala"选择"Mark Directory as"->"Sources Root"
5.若右击"scala"文件夹没有"Scala class"显示，则选择"File"->"Project Structure"->"Global Libraries"，点击"-", 把scala-sdk除去，然后再点击"+",把scala-sdk添加进来，此时就能创建"Scala Class"
```

9.breakable结构（具体用break跳出循环）可以跳出循环

10.lazy：懒加载

