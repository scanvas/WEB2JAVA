# 常量

Java中的常量，是在程序运行期间，固定不会变都量。

与前端中的常量概念一样，但是在es6中常量使用const关键字，如：
```javascript 
const web = "JavaScript";
```

在Java中没有```const```这种概念。常量就是常量。也不用过度的深究。

### 常量的分类:

常量的分类其实就是Java中常用的基本数据类型，Java中的数据类型要比Js中多出来很多，也复杂的多。后面我们会一一学习。

1. 字符串常量： 凡是用双引号引起来的部分，例如："abc"、"123"、"1.5"、"大前端"
2. 整数常量： 直接写的整数，不包括小数。例如： 1、24、-5（**注意：**前端只有`Number`这个数据类型，表示数字，部分整数与小数。Java中分整数和小数两种代表数字类型，区分更复杂，后面会讲到 ）
3. 浮点数常量：有小数点的数字。例如：2.5、0.5
4. 字符常量：凡是用单引号引起来的部分，例如："a"、"3"、"."、"前"（**注意：**前端只有`String`这个数据类型，表示字符串。Java中字符类型，单引号中有且只有一个字符）
5. 布尔常量： true、false
6. 空常量： null

我们可以一起在命令行中打印一下上面的这些常量。我们可以把之前的`HelloWorld.java`再写一遍，加深记忆。

这里也是建议新建一个文件夹，把自己学习用的代码放在这个文件夹里。

```java
  public class HelloWorlld{
    public static void main(String[] agrs){
      //字符串常量
      System.out.println("HelloWorld！");
      //空字符串是存在的，也是可以打印的
      System.out.println("");
      //整数常量
      System.out.println(200);
      //浮点数常量
      System.out.println(2.5);
      //字符常量
	  System.out.println('a');
      //字符常量的单引号中，必须有且只有一个字符。否则会报错。
      //System.out.println('');
      //System.out.println('a');
      //布尔常量
	  System.out.println(true);
      //空常量不能直接打印
      //Syetem.out.println(null);
    }
  }
```

多敲几遍，保证全部输出正确。**注意：** 这里的`;`分号是必须要的，不像js中可有可无。
