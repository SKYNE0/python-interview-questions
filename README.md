# 第一部分 Python基础篇（80题） 

### 1、为什么学习Python？

```
高层语言 ：无需考虑如何管理你的程序使用的内存一类的底层细节等。

可移植性 ：由于Python的开源本质，它已经被移植在许多平台上。

面向对象 ：Python既支持面向过程的编程也支持面向对象的编程。

可扩展性 ：Python编辑的程序中可以直接调用部分C或C++ 开发的程序。

可嵌入性 ：可以把Python嵌入C/C++程序，从而向程序用户提供脚本功能。

丰富的库 ： Python庞大的标准库可以帮助处理各种工作，几乎无所不能。

规范的代码 ： Python不需要编译成二进制代码的强制缩进方式，使得代码具有较好的可读性。

自己说：来自某培训机构的宣传。
```

### 2、通过什么途径学习的Python？

##### 参考下面两篇知乎文章：
##### [1,关于 Python 的经典入门书籍有哪些？](https://www.zhihu.com/question/19593179)
##### [2,怎么用最短时间高效而踏实地学习 Python？](https://www.zhihu.com/question/28530832)
##### 自己说：Python确实是门语法简洁优美，入门简单的语言，但如何写出极具Pythonic风格的代码，是需要耐心学习，刻苦练习的。

### 3、Python和Java、PHP、C、C#、C++等其他语言的对比？
```
 C语言，它既有高级语言的特点，又具有汇编语言的特点，它是结构式语言。C语言应用指针：可以直接进行靠近硬件的操作，
 但是C的指针操作不做保护，也给它带来了很多不安全的因素。C++在这方面做了改进，在保留了指针操作的同时又增强了安全性，
 受到了一些用户的支持，但是，由于这些改进增加语言的复杂度，也为另一部分所诟病。Java则吸取了C++的教训，取消了指针操作，
 也取消了C++改进中一些备受争议的地方，在安全性和适合性方面均取得良好的效果，但其本身解释在虚拟机中运行，运行效率低于C++/C。
 一般而言，C，C++，java被视为同一系的语言，它们长期占据着程序使用榜的前三名。
 
C语言的优点：简洁紧凑、灵活方便；运算符丰富；数据类型丰富；表达方式灵活实用；允许直接访问物理地址，对硬件进行操作；
生成目标代码质量高，程序执行效率高；可移植性好；表达力强；

C语言的缺点：C语言的缺点主要表现在数据的封装性上，这一点使得C在数据的安全性上有很大缺陷，这也是C和C++的一大区别。
C语言的语法限制不太严格，对变量的类型约束不严格，影响程序的安全性，对数组下标越界不作检查等。从应用的角度，C语言比其他高级语言较难掌握。也就是说，对用C语言的人，要求对程序设计更熟练一些。


C#语言，C#是微软公司发布的一种面向对象的、运行于.NET Framework之上的高级程序设计语言。
C#看起来与Java有着惊人的相似；它包括了诸如单一继承、接口、与Java几乎同样的语法和编译成中间代码再运行的过程。
但是C#与Java有着明显的不同，它借鉴了Delphi的一个特点，与COM（组件对象模型）是直接集成的，
而且它是微软公司 .NET windows网络框架的主角。首先，C# 和JAVA一样，简直就是照搬了C++的部分语法，
因此，对于数量众多的C++程序员学习起来很容易上手，另外，对于新手来说，比C++要简单一些。
其次，Windows是占垄断地位的平台，而开发Windows应用，当然微软的声音是不能忽略的。最重要的是，
相对于C++，用C# 开发应用软件可以大大缩短开发周期，同时可以利用原来除用户界面代码之外的C++代码。


Java语言，Java是一种可以撰写跨平台应用软件的面向对象的程序设计语言，是由Sun Microsystems公司于1995年5月推出的Java程序设计语言和Java平台（即JavaSE, JavaEE, JavaME）的总称。
Java 技术具有卓越的通用性、高效性、平台移植性和安全性，广泛应用于个人PC、数据中心、游戏控制台、科学超级计算机、移动电话和互联网，
同时拥有全球最大的开发者专业社群。在全球云计算和移动互联网的产业环境下，Java更具备了显著优势和广阔前景。
Java的优势，与传统程序不同，Sun 公司在推出 Java 之际就将其作为一种开放的技术。全球数以万计的 Java 开发公司被要求所设计的 Java软件必须相互兼容。
“Java 语言靠群体的力量而非公司的力量”是Sun公司的口号之一，并获得了广大软件开发商的认同。这与微软公司所倡导的注重精英和封闭式的模式完全不同。

Sun 公司对 Java 编程语言的解释是：Java 编程语言是个简单、面向对象、分布式、解释性、健壮、安全与系统无关、可移植、高性能、多线程和动态的语言。

php语言，PHP（PHP: Hypertext Preprocessor的缩写，中文名：“PHP：超文本预处理器”）是一种通用开源脚本语言。语法吸收了C语言、Java和Perl的特点，
入门门槛较低，易于学习，使用广泛，主要适用于Web开发领域。

特性：PHP 独特的语法混合了 C、Java、Perl 以及 PHP 自创新的语法；PHP可以比CGI或者Perl更快速的执行动态网页——动态页面方面，
与其他的编程语言相比，PHP是将程序嵌入到HTML文档中去执行，执行效率比完全生成htmL标记的CGI要高许多，PHP具有非常强大的功能，
所有的CGI的功能PHP都能实现； PHP支持几乎所有流行的数据库以及操作系统；最重要的是PHP可以用C、C++进行程序的扩展。
 
python语言，是一种面向对象、直译式计算机程序设计语言，Python语法简洁而清晰，具有丰富和强大的类库。它常被昵称为胶水语言，
它能够很轻松的把用其他语言制作的各种模块（尤其是C/C++）轻松地联结在一起。
常见的一种应用情形是，使用python快速生成程序的原型（有时甚至是程序的最终界面），然后对其中有特别要求的部分，用更合适的语言改写。

Python是完全面向对象的语言。函数、模块、数字、字符串都是对象。并且完全支持继承、重载、派生、多继承，有益于增强源代码的复用性。
Python支持重载运算符和动态类型。相对于Lisp这种传统的函数式编程语言，Python对函数式设计只提供了有限的支持。
有两个标准库(functools, itertools)提供了Haskell和Standard ML中久经考验的函数式程序设计工具。Python本身被设计为可扩充的。
并非所有的特性和功能都集成到语言核心。Python提供了丰富的API和工具，以便程序员能够轻松地使用C语言、C++、Cython来编写扩充模块。
Python编译器本身也可以被集成到其它需要脚本语言的程序内。因此，很多人还把Python作为一种“胶水语言”（glue language）使用。
使用Python将其他语言编写的程序进行集成和封装
```

##### 自己说：内容来自[C、C++、C#、Java、php、python语言的内在特性及区别](https://blog.csdn.net/zllzb2011/article/details/47169479)
##### 参考阅读：
##### [编程语言拟人化（1）：Java、C++、Python、Ruby、PHP、C#、JS](http://blog.jobbole.com/63311/) 
##### [趣文：编程语言拟人化（第二弹）](http://blog.jobbole.com/63036/)

### 4、简述解释型和编译型编程语言？
```
概念：

    编译型语言：把做好的源程序全部编译成二进制代码的可运行程序。然后，可直接运行这个程序。
    解释型语言：把做好的源程序翻译一句，然后执行一句，直至结束！

区别：

    编译型语言，执行速度快、效率高；依赖编译器、跨平台性差些。如C、C++、Delphi、Pascal，Fortran。
    解释型语言，执行速度慢、效率低；依赖解释器、跨平台性好。如Java、Basic.

通俗的讲，编译语言是在编译后可以直接运行，而解释语言的执行需要一个解释环境。

 java很特殊，java程序也需要编译，但是没有直接编译称为机器语言，而是编译称为字节码，然后用解释方式执行字节码。

**********************************************************************************************

计算机不能直接理解高级语言，只能直接理解机器语言，所以必须要把高级语言翻译成机器语言，计算机才能值型高级语言编写的程序。

翻译的方式有两种，一个是编译，一个是解释。两种方式只是翻译的时间不同。编译型语言写的程序执行之前，需要一个专门的编译过程，
把程序编译成为机器语言的文件，比如exe文件，以后要运行的话就不用重新翻译了，直接使用编译的结果就行了（exe文件），因为翻译只做了一次，
运行时不需要翻译，所以编译型语言的程序执行效率高。

解释则不同，解释性语言的程序不需要编译，省了道工序，解释性语言在运行程序的时候才翻译，比如解释性basic语言，
专门有一个解释器能够直接执行basic程序，每个语句都是执行的时候才翻译。这样解释性语言每执行一次就要翻译一次，效率比较低。

编译型与解释型，两者各有利弊。前者由于程序执行速度快，同等条件下对系统要求较低，因此像开发操作系统、大型应用程序、数据库系统等时都采用它，像C/C++、Pascal/Object Pascal（Delphi）等都是编译语言，
而一些网页脚本、服务器脚本及辅助开发接口这样的对速度要求不高、对不同系统平台间的兼容性有一定要求的程序则通常使用解释性语言，如JavaScript、VBScript、Perl、Python、Ruby、MATLAB 等等。
```
##### 详细介绍：
#####[编译型与解释型、动态语言与静态语言、强类型语言与弱类型语言的区别](https://juejin.im/entry/58918ef0128fe1006c92e1a4)
##### [简述编译型与解释型编程语言](https://www.i3geek.com/archives/583)

### 5、Python解释器种类以及特点？
```
当我们编写Python代码时，我们得到的是一个包含Python代码的以.py为扩展名的文本文件。要运行代码，就需要Python解释器去执行.py文件。

由于整个Python语言从规范到解释器都是开源的，所以理论上，只要水平够高，任何人都可以编写Python解释器来执行Python代码（当然难度很大）。
事实上，确实存在多种Python解释器。
1,CPython

当我们从Python官方网站下载并安装好Python 3.5后，我们就直接获得了一个官方版本的解释器：CPython。
这个解释器是用C语言开发的，所以叫CPython。在命令行下运行python就是启动CPython解释器。
CPython是使用最广的Python解释器。教程的所有代码也都在CPython下执行。

2,IPython
IPython是基于CPython之上的一个交互式解释器，也就是说，IPython只是在交互方式上有所增强，但是执行Python代码的功能和CPython是完全一样的。
好比很多国产浏览器虽然外观不同，但内核其实都是调用了IE。
CPython用>>>作为提示符，而IPython用In [序号]:作为提示符。

3,PyPy

PyPy是另一个Python解释器，它的目标是执行速度。PyPy采用JIT技术，对Python代码进行动态编译（注意不是解释），所以可以显著提高Python代码的执行速度。
绝大部分Python代码都可以在PyPy下运行，但是PyPy和CPython有一些是不同的，这就导致相同的Python代码在两种解释器下执行可能会有不同的结果。
如果你的代码要放到PyPy下执行，就需要了解PyPy和CPython的不同点。

4,Jython
Jython是运行在Java平台上的Python解释器，可以直接把Python代码编译成Java字节码执行。

5,IronPython
IronPython和Jython类似，只不过IronPython是运行在微软.Net平台上的Python解释器，可以直接把Python代码编译成.Net的字节码。

小结:
Python的解释器很多，但使用最广泛的还是CPython。如果要和Java或.Net平台交互，最好的办法不是用Jython或IronPython，
而是通过网络调用来交互，确保各程序之间的独立性。
```
### 6、位和字节的关系？
```
最小的存储单位称为位（bit）：
只能容纳两个值（0或1）之一，不能在一个位中存储更多的信息。位是计算机存储的基本单位。
字节(byte)是常用的计算机存储单位。
字节的标准定义：一个字节均为8位。由于上述所讲每个位或者是0或者是1，所以一个8位的字节包含256种可能的0，1组合
```
### 7、b、B、KB、MB、GB 的关系？
```
1024B=1KB,1024KB=1MB,
1024MB=1GB,1024GB=1TB.
他们是计算机中表示容量的单位。都是2的10次方进制的。
他们可以用来表示内存、硬盘等的容量。
```

### 8、请至少列举5个 PEP8 规范（越多越好）。
```
一 代码编排

二 文档编排

三 空格的使用

四 注释

五 文档描述

六 命名规范

七 编码建议
```
##### 详细介绍：
##### [PEP 8 -- Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/)
##### [PEP8 Python 编码规范整理](https://www.douban.com/note/134971609/)

### 9、通过代码实现如下转换：

### 二进制转换成十进制：v = “0b1111011”

### 十进制转换成二进制：v = 18 

### 八进制转换成十进制：v = “011” 

### 十进制转换成八进制：v = 30 

### 十六进制转换成十进制：v = “0x12” 

### 十进制转换成十六进制：v = 87

##### 参考阅读：
##### [Python各进制间的转换](https://blog.csdn.net/SeeTheWorld518/article/details/47752925)
##### [Python实现任意进制之间的转换 ](http://blog.51cto.com/djangor/1401229)

### 10、请编写一个函数实现将IP地址转换成一个整数。

```

 如 10.3.9.12 转换规则为：

 

  10           00001010

  3            00000011

  9            00001001

  12           00001100

```

#### 再将以上二进制拼接起来计算十进制结果：00001010 00000011 00001001 00001100 = ？
```
def ipTodec(ip):
    """
    :param ip: char IP地址：192.168.1.1
    :return:
    """
    dec_ips = ip.split('.')
    bin_ips = " "
    
    for decnum in dec_ips:
        bin_ele = bin(int(decnum))[2::]
        bin_ips += bin_ele
        
    print(bin_ips)
    print(int(bin_ips, 2))
```
##### 自己说：自己写的，可能不太好。

### 11、python递归的最大层数？
```
Python确实有递归次数限制，默认最大次数为1000
但可以使用下面的方法来指定次数。
sys.setrecursionlimit(limit)

Set the maximum depth of the Python interpreter stack to limit. This limit prevents infinite recursion from causing an overflow of the C stack and crashing Python.

The highest possible limit is platform-dependent. A user may need to set the limit higher when she has a program that requires deep recursion and a platform that supports a higher limit. This should be done with care, because a too-high limit can lead to a crash.

```
##### 参考阅读：
##### [28.1. sys — System-specific parameters and functions](https://docs.python.org/2/library/sys.html#sys.setrecursionlimit)

### 12、求结果：

```
 v1 = 1 or 3

 v2 = 1 and 3

 v3 = 0 and 2 and 1

 v4 = 0 and 2 or 1

 v5 = 0 and 2 or 1 or 4

 v6 = 0 or False and 1

```
```
1
3
0
1
1
False
```
##### 参考阅读：
##### [	python中and-or语法](https://blog.csdn.net/permike/article/details/52311211)

### 13、ascii、unicode、utf-8、gbk 区别？
```
最早只有127个字母被编码到计算机里，也就是大小写英文字母、数字和一些符号，这个编码表被称为ASCII编码，比如大写字母A的编码是65，小写字母z的编码是122。

但是要处理中文显然一个字节是不够的，至少需要两个字节，而且还不能和ASCII编码冲突，所以，中国制定了GB2312编码，用来把中文编进去。

你可以想得到的是，全世界有上百种语言，日本把日文编到Shift_JIS里，韩国把韩文编到Euc-kr里，各国有各国的标准，就会不可避免地出现冲突，结果就是，在多语言混合的文本中，显示出来会有乱码。

因此，Unicode应运而生。Unicode把所有语言都统一到一套编码里，这样就不会再有乱码问题了。

Unicode标准也在不断发展，但最常用的是用两个字节表示一个字符（如果要用到非常偏僻的字符，就需要4个字节）。现代操作系统和大多数编程语言都直接支持Unicode。

新的问题又出现了：如果统一成Unicode编码，乱码问题从此消失了。但是，如果你写的文本基本上全部是英文的话，用Unicode编码比ASCII编码需要多一倍的存储空间，在存储和传输上就十分不划算。

所以，本着节约的精神，又出现了把Unicode编码转化为“可变长编码”的UTF-8编码。UTF-8编码把一个Unicode字符根据不同的数字大小编码成1-6个字节，常用的英文字母被编码成1个字节，汉字通常是3个字节，只有很生僻的字符才会被编码成4-6个字节。如果你要传输的文本包含大量英文字符，用UTF-8编码就能节省空间。

UTF-8编码有一个额外的好处，就是ASCII编码实际上可以被看成是UTF-8编码的一部分，所以，大量只支持ASCII编码的历史遗留软件可以在UTF-8编码下继续工作。
```
##### 详细介绍：
##### [ASCII，Unicode 和 UTF-8 的故事](https://juejin.im/entry/59434c3161ff4b006cd280a1)
##### [字符串和编码](https://www.liaoxuefeng.com/wiki/0014316089557264a6b348958f449949df42a6d3a2e542c000/001431664106267f12e9bef7ee14cf6a8776a479bdec9b9000)

### 14、字节码和机器码的区别？
```
什么是机器码
机器码

机器码(machine code)，学名机器语言指令，有时也被称为原生码（Native Code），是电脑的CPU可直接解读的数据。

通常意义上来理解的话，机器码就是计算机可以直接执行，并且执行速度最快的代码。

用机器语言编写程序，编程人员要首先熟记所用计算机的全部指令代码和代码的涵义。手编程序时，程序员得自己处理每条指令和每一数据的存储分配和输入输出，
还得记住编程过程中每步所使用的工作单元处在何种状态。这是一件十分繁琐的工作，编写程序花费的时间往往是实际运行时间的几十倍或几百倍。
而且，编出的程序全是些0和1的指令代码，直观性差，还容易出错。现在，除了计算机生产厂家的专业人员外，绝大多数的程序员已经不再去学习机器语言了。

    机器语言是微处理器理解和使用的，用于控制它的操作二进制代码。
    8086到Pentium的机器语言指令长度可以从1字节到13字节。
    尽管机器语言好像是很复杂的，然而它是有规律的。
    存在着多至100000种机器语言的指令。这意味着不能把这些种类全部列出来。

总结：机器码是电脑CPU直接读取运行的机器指令，运行速度最快，但是非常晦涩难懂，也比较难编写，一般从业人员接触不到。

什么是字节码
字节码

字节码（Bytecode）是一种包含执行程序、由一序列 op 代码/数据对 组成的二进制文件。字节码是一种中间码，
它比机器码更抽象，需要直译器转译后才能成为机器码的中间代码。

通常情况下它是已经经过编译，但与特定机器码无关。字节码通常不像源码一样可以让人阅读，而是编码后的数值常量、引用、指令等构成的序列。

字节码主要为了实现特定软件运行和软件环境、与硬件环境无关。字节码的实现方式是通过编译器和虚拟机器。编译器将源码编译成字节码，
特定平台上的虚拟机器将字节码转译为可以直接执行的指令。字节码的典型应用为Java bytecode。

字节码在运行时通过JVM（JAVA虚拟机）做一次转换生成机器指令，因此能够更好的跨平台运行。

总结：字节码是一种中间状态（中间码）的二进制代码（文件）。需要直译器转译后才能成为机器码。
```
##### 参考阅读：
##### [机器码和字节码](https://www.cnblogs.com/qiumingcheng/p/5400265.html)
##### [Python 源码剖析 - 字节码和虚拟机](https://juejin.im/entry/5874ba362f301e00575524c4)

### 15、三元运算规则以及应用场景？
```
三元运算符就是在赋值变量的时候，可以直接加判断，然后赋值
格式：[on_true] if [expression] else [on_false]
res = 值1 if 条件 else 值2
1.举例说明：
a =1
b = 2

c= a if a>1 else b #如果a大于1的话，c=a，否则c=b
```

### 16、列举 Python2和Python3的区别？
```
     一、python2  的代码混乱 重复较多 冗余  因为当时来编写的人有C 语言的大牛 和 java的大牛等各种大神 所以里面都含有各种语言的影子
            python3  经过龟叔的一个暑假的整理 终于在2018年11月 统一了代码  源码规范 清晰 简单优美。 

    二、python3  print（"内容"）
           python2 ptint()   或者print '内容'

   三、python3 编码：utf-8
          python2编码： 默认编码：ascii     解决办法：在首行 #    -*- ending：utf-8-*-

   四、用户交互 input
          python2:  raw-input（）

          python3:input ()  

五、python2x  :unicode 默认2个字节表示一个字符  可以在LINUX 编译安装时做调整
      python3x：unicode 默认是4个字节表示一个字符 

六、python2x  没有nonlocal
      python3x   加入的

七 、python3x  新建的包里面的init文件如果你删除该文件  包照样可以被调用
        python2x  新建的包如果没有init文件 则包不能够被调用 直接报错

八、python2 中的经典类 遍历方法是以深度优先    新式类是以广度优先 
      python3 中不存在经典类  所有的类都是新式类  所以都是广度优先
```
##### 详细介绍：
##### [Python2和Python3的差异](https://www.cnblogs.com/kendrick/p/7478304.html)

### 17、用一行代码实现数值交换：

 ```
 a = 1

 b = 2
 
 a, b = b, a
```

### 18、Python3和Python2中 int 和 long的区别？
```
Python 2有为非浮点数准备的int和long类型。int类型的最大值不能超过sys.maxint，而且这个最大值是平台相关的。
可以通过在数字的末尾附上一个L来定义长整型，显然，它比int类型表示的数字范围更大。在Python 3里，
只有一种整数类型int，大多数情况下，它很像Python 2里的长整型。由于已经不存在两种类型的整数，所以就没有必要使用特殊的语法去区别他们。

Notes  	Python 2 	         Python 3

① 	x =1000000000000L 	  x =1000000000000

② 	x =0xFFFFFFFFFFFFL 	  x =0xFFFFFFFFFFFF

③ 	    long(x) 	            int(x)

④ 	  type(x)is long 	     type(x)is int

⑤ 	isinstance(x,long) 	isinstance(x,int)

在Python 2里的十进制长整型在Python 3里被替换为十进制的普通整数。
在Python 2里的十六进制长整型在Python 3里被替换为十六进制的普通整数。
在Python 3里，由于长整型已经不存在了，自然原来的long()函数也没有了。为了强制转换一个变量到整型，可以使用int()函数。
检查一个变量是否是整型，获得它的数据类型，并与一个int类型(不是long)的作比较。
你也可以使用isinstance()函数来检查数据类型；再强调一次，使用int，而不是long，来检查整数类型。
```

### 19、xrange和range的区别？
```
range产生的是一个列表，而xrange产生的是一个生成器器的。

所以对于较大的集合时候，xrange比range性能好。

因为range一次把所以数据都返回，而xrange每次调用返回其中的一个值
```

### 20、文件操作时：xreadlines和readlines的区别？
```
原理同19题一样。
```

### 21、列举布尔值为False的常见值？
```
False  None  0 ‘’ “” [] {} ()
```

### 22、字符串、列表、元组、字典每个常用的5个方法？
```
str   .join()  .split()  .lower()  .upper()  .strip()
list   .append()  .pop()  .reverse() .sort()  .remove()
tuple  .index()  .count()  len(atuple)  max(atuple)  min(tuple)
dict   .get()  .keys()  .values()  .iters()  .update()
```

### 23、lambda表达式格式以及应用场景？
```
python 使用 lambda 表达式来创建匿名函数

lambda只是一个表达式，函数体比def简单很多
lambda的主体是一个表达式，而不是一个代码块。仅仅能在lambda表达式中封装有限的逻辑进去
lambda函数拥有自己的名字空间，且不能访问自有参数列表之外或全局名字空间里的参数
虽然lambda函数看起来只能写一行，却不等同于C或C++的内联函数，后者的目的是调用小函数时不占用栈内存从而增加运行效率

lambda函数的语法只包含一个语句： lambda [arg1 [,arg2,…..argn]]:expression 

lambda 函数与Python的函数式编程有很大联系，比如：map(), reduce(), filter()
```
##### 参考阅读：
##### [python中lambda表达式应用](https://www.cnblogs.com/Eva-J/p/4977819.html)

### 24、pass的作用？
```
Python pass是空语句，是为了保持程序结构的完整性。

pass 不做任何事情，一般用做占位语句。
```
### 25、*arg和**kwarg作用?
```
可变参数 *args 允许你传入0个或任意个参数，这些可变参数在函数调用时自动组装为一个tuple,

而 关键字参数 **kwargs 允许你传入0个或任意个含参数名的参数，这些关键字参数在函数内部自动组装为一个dict。
```

### 26、is和==的区别？
```
Python中的对象包含三要素：id、type、value
其中id用来唯一标识一个对象，type标识对象的类型，value是对象的值
is判断的是a对象是否就是b对象，是通过id来判断的
==判断的是a对象的值是否和b对象的值相等，是通过value来判断的

简单说就是：
is 对比地址   ==  对比值
```

### 27、简述Python的深浅拷贝以及应用场景？
```
= 赋值：数据完全共享（=赋值是在内存中指向同一个对象，如果是可变(mutable)类型，比如列表，修改其中一个，另一个必定改变
如果是不可变类型(immutable),比如字符串，修改了其中一个，另一个并不会变

浅拷贝：数据半共享（复制其数据独立内存存放，但是只拷贝成功第一层）

深拷贝：数据完全不共享（复制其数据完完全全放独立的一个内存，完全拷贝，数据不共享）
```
##### 参考阅读：
##### [Python深浅拷贝](https://www.jianshu.com/p/c1e561d8ca7c)

### 28、Python垃圾回收机制？
```
Python GC主要使用引用计数（reference counting）来跟踪和回收垃圾。在引用计数的基础上，
通过“标记-清除”（mark and sweep）解决容器对象可能产生的循环引用问题，
通过“分代回收”（generation collection）以空间换时间的方法提高垃圾回收效率。

1 引用计数

PyObject是每个对象必有的内容，其中ob_refcnt就是做为引用计数。当一个对象有新的引用时，它的ob_refcnt就会增加，
当引用它的对象被删除，它的ob_refcnt就会减少.引用计数为0时，该对象生命就结束了。

优点:

    简单
    实时性

缺点:

    维护引用计数消耗资源
    循环引用

2 标记-清除机制

基本思路是先按需分配，等到没有空闲内存的时候从寄存器和程序栈上的引用出发，遍历以对象为节点、以引用为边构成的图，
把所有可以访问到的对象打上标记，然后清扫一遍内存空间，把所有没标记的对象释放。
3 分代技术

分代回收的整体思想是：将系统中的所有内存块根据其存活时间划分为不同的集合，每个集合就成为一个“代”，
垃圾收集频率随着“代”的存活时间的增大而减小，存活时间通常利用经过几次垃圾回收来度量。

Python默认定义了三代对象集合，索引数越大，对象存活时间越长。

举例： 当某些内存块M经过了3次垃圾收集的清洗之后还存活时，我们就将内存块M划到一个集合A中去，而新分配的内存都划分到集合B中去。
当垃圾收集开始工作时，大多数情况都只对集合B进行垃圾回收，而对集合A进行垃圾回收要隔相当长一段时间后才进行，
这就使得垃圾收集机制需要处理的内存少了，效率自然就提高了。在这个过程中，集合B中的某些内存块由于存活时间长而会被转移到集合A中，
当然，集合A中实际上也存在一些垃圾，这些垃圾的回收会因为这种分代的机制而被延迟。
```

### 29、Python的可变类型和不可变类型？
```
Python的每个对象都分为可变和不可变，
主要的核心类型中，
不可变 : 数字、字符串、元组
可变 : 列表、字典

对不可变类型的变量重新赋值，实际上是重新创建一个不可变类型的对象，
并将原来的变量重新指向新创建的对象（如果没有其他变量引用原有对象的话（即引用计数为0），原有对象就会被回收）。
```

### 30、求结果：
```

 v = dict.fromkeys(['k1','k2'],[])

 v[‘k1’].append(666)

 print(v)

 v[‘k1’] = 777

 print(v)

{'k1': [666], 'k2': [666]}
{'k1': 777, 'k2': [666]}
该题上面的几道题的综合考察，请仔细思考一下。
 ```

### 31、求结果：

![](https://images2018.cnblogs.com/blog/425762/201805/425762-20180523191729906-771120081.png)

### 32、列举常见的内置函数？
```
abs() 	divmod() 	input() 	open() 	staticmethod()
all() 	enumerate() 	int() 	ord() 	str()
any() 	eval() 	isinstance() 	pow() 	sum()
basestring() 	execfile() 	issubclass() 	print() 	super()
bin() 	file() 	iter() 	property() 	tuple()
bool() 	filter() 	len() 	range() 	type()
bytearray() 	float() 	list() 	raw_input() 	unichr()
callable() 	format() 	locals() 	reduce() 	unicode()
chr() 	frozenset() 	long() 	reload() 	vars()
classmethod() 	getattr() 	map() 	repr() 	xrange()
cmp() 	globals() 	max() 	reverse() 	zip()
compile() 	hasattr() 	memoryview() 	round() 	__import__()
complex() 	hash() 	min() 	set() 	
delattr() 	help() 	next() 	setattr() 	
dict() 	hex() 	object() 	slice() 	
dir() 	id() 	oct() 	sorted()
```

### 33、filter、map、reduce的作用？

### 34、一行代码实现9*9乘法表

### 35、如何安装第三方模块？以及用过哪些第三方模块？

### 36、至少列举8个常用模块都有那些？

### 37、re的match和search区别？

### 38、什么是正则的贪婪匹配？

### 39、求结果： a. [ i % 2 for i in range(10) ] b. ( i % 2 for i in range(10) )

### 40、求结果： a. 1 or 2 b. 1 and 2 c. 1 < (2==2) d. 1 < 2 == 2

### 41、def func(a,b=[]) 这种写法有什么坑？

### 42、如何实现 “1,2,3” 变成 [‘1’,’2’,’3’] ?

### 43、如何实现[‘1’,’2’,’3’]变成[1,2,3] ?

### 44、比较： a = [1,2,3] 和 b = [(1),(2),(3) ] 以及 b = [(1,),(2,),(3,) ] 的区别？

### 45、如何用一行代码生成[1,4,9,16,25,36,49,64,81,100] ?

### 46、一行代码实现删除列表中重复的值 ?

### 47、如何在函数中设置一个全局变量 ?

### 48、logging模块的作用？以及应用场景？

### 49、请用代码简答实现stack 。

### 50、常用字符串格式化哪几种？

### 51、简述 生成器、迭代器、可迭代对象 以及应用场景？

### 52、用Python实现一个二分查找的函数。

### 53、谈谈你对闭包的理解？

### 54、os和sys模块的作用？

### 55、如何生成一个随机数？

### 56、如何使用python删除一个文件？

### 57、谈谈你对面向对象的理解？

### 58、Python面向对象中的继承有什么特点？

### 59、面向对象深度优先和广度优先是什么？

### 60、面向对象中super的作用？

### 61、是否使用过functools中的函数？其作用是什么？

### 62、列举面向对象中带爽下划线的特殊方法，如：__new__、__init__

### 63、如何判断是函数还是方法？

### 64、静态方法和类方法区别？

### 65、列举面向对象中的特殊成员以及应用场景

### 66、1、2、3、4、5 能组成多少个互不相同且无重复的三位数

### 67、什么是反射？以及应用场景？

### 68、metaclass作用？以及应用场景？

### 69、用尽量多的方法实现单例模式。

### 70、装饰器的写法以及应用场景。

### 71、异常处理写法以及如何主动跑出异常（应用场景）

### 72、什么是面向对象的mro

### 73、isinstance作用以及应用场景？
 
### 74、写代码并实现： 
```
 Given an array of integers, return indices of the two numbers such that they add up to a specific target.You may assume that each input would 

 have exactly one solution, and you may not use the same element twice.

 Example:

     Given nums = [2, 7, 11, 15], target = 9,
    
     Because nums[0] + nums[1] = 2 + 7 = 9,
    
                return [0, 1]

 ```

### 75、json序列化时，可以处理的数据类型有哪些？如何定制支持datetime类型？

### 76、json序列化时，默认遇到中文会转换成unicode，如果想要保留中文怎么办？

### 77、什么是断言？应用场景？

### 78、有用过with statement吗？它的好处是什么？

### 79、使用代码实现查看列举目录下的所有文件。

### 80、简述 yield和yield from关键字。

----
# 第二部分 网络编程和并发（34题）


### 1、简述 OSI 七层协议。

### 2、什么是C/S和B/S架构？

### 3、简述 三次握手、四次挥手的流程。

### 4、什么是arp协议？

### 5、TCP和UDP的区别？

### 6、什么是局域网和广域网？

### 7、为何基于tcp协议的通信比基于udp协议的通信更可靠？

### 8、什么是socket？简述基于tcp协议的套接字通信流程。

### 9、什么是粘包？ socket 中造成粘包的原因是什么？ 哪些情况会发生粘包现象？

### 10、IO多路复用的作用？

### 11、什么是防火墙以及作用？

### 12、select、poll、epoll 模型的区别？

### 13、简述 进程、线程、协程的区别 以及应用场景？

### 14、GIL锁是什么鬼？

### 15、Python中如何使用线程池和进程池？

### 16、threading.local的作用？

### 17、进程之间如何进行通信？

### 18、什么是并发和并行？

### 19、进程锁和线程锁的作用？

### 20、解释什么是异步非阻塞？

### 21、路由器和交换机的区别？

### 22、什么是域名解析？

### 23、如何修改本地hosts文件？

### 24、生产者消费者模型应用场景及优势？

### 25、什么是cdn？

### 26、LVS是什么及作用？

### 27、Nginx是什么及作用？

### 28、keepalived是什么及作用?

### 29、haproxy是什么以及作用？

### 30、什么是负载均衡？

### 31、什么是rpc及应用场景？

### 32、简述 asynio模块的作用和应用场景。

### 33、简述 gevent模块的作用和应用场景。

### 34、twisted框架的使用和应用？

---

# 第三部分 数据库和缓存（46题）


### 1、列举常见的关系型数据库和非关系型都有那些？

### 2、MySQL常见数据库引擎及比较？

### 3、简述数据三大范式？

### 4、什么是事务？MySQL如何支持事务？

### 5、简述数据库设计中一对多和多对多的应用场景？

### 6、如何基于数据库实现商城商品计数器？

### 7、常见SQL（必备）

[详见武沛齐博客](https://www.cnblogs.com/wupeiqi/articles/5729934.html)

### 8、简述触发器、函数、视图、存储过程？

### 9、MySQL索引种类

### 10、索引在什么情况下遵循最左前缀的规则？

### 11、主键和外键的区别？

### 12、MySQL常见的函数？

### 13、列举 创建索引但是无法命中索引的8种情况。

### 14、如何开启慢日志查询？

### 15、数据库导入导出命令（结构+数据）？

### 16、数据库优化方案？

### 17、char和varchar的区别？

### 18、简述MySQL的执行计划？

### 19、在对name做了唯一索引前提下，简述以下区别： 

```
 select * from tb where name = ‘Oldboy-Wupeiqi’ 

 select * from tb where name = ‘Oldboy-Wupeiqi’ limit 1
``` 

### 20、1000w条数据，使用limit offset 分页时，为什么越往后翻越慢？如何解决？

### 21、什么是索引合并？

### 22、什么是覆盖索引？

### 23、简述数据库读写分离？

### 24、简述数据库分库分表？（水平、垂直）

### 25、redis和memcached比较？

### 26、redis中数据库默认是多少个db 及作用？

### 27、python操作redis的模块？

### 28、如果redis中的某个列表中的数据量非常大，如果实现循环显示每一个值？

### 29、redis如何实现主从复制？以及数据同步机制？

### 30、redis中的sentinel的作用？

### 31、如何实现redis集群？

### 32、redis中默认有多少个哈希槽？

### 33、简述redis的有哪几种持久化策略及比较？

### 34、列举redis支持的过期策略。

### 35、MySQL 里有 2000w 数据，redis 中只存 20w 的数据，如何保证 redis 中都是热点数据？ 

### 36、写代码，基于redis的列表实现 先进先出、后进先出队列、优先级队列。

### 37、如何基于redis实现消息队列？

### 38、如何基于redis实现发布和订阅？以及发布订阅和消息队列的区别？

### 39、什么是codis及作用？

### 40、什么是twemproxy及作用？

### 41、写代码实现redis事务操作。

### 42、redis中的watch的命令的作用？

### 43、基于redis如何实现商城商品数量计数器？

### 44、简述redis分布式锁和redlock的实现机制。

### 45、什么是一致性哈希？Python中是否有相应模块？

### 46、如何高效的找到redis中所有以oldboy开头的key？

---

# 第四部分 前端、框架和其他（155题）


### 1、谈谈你对http协议的认识。

### 2、谈谈你对websocket协议的认识。

### 3、什么是magic string ？

### 4、如何创建响应式布局？

### 5、你曾经使用过哪些前端框架？

### 6、什么是ajax请求？并使用jQuery和XMLHttpRequest对象实现一个ajax请求。

### 7、如何在前端实现轮训？

### 8、如何在前端实现长轮训？

### 9、vuex的作用？

### 10、vue中的路由的拦截器的作用？

### 11、axios的作用？

### 12、列举vue的常见指令。

### 13、简述jsonp及实现原理？

### 14、是什么cors ？

### 15、列举Http请求中常见的请求方式？

### 16、列举Http请求中的状态码？

### 17、列举Http请求中常见的请求头？

### 18、看图写结果：

![](https://images2018.cnblogs.com/blog/425762/201805/425762-20180523193331193-1780213562.png)



### 19、看图写结果：

![](https://images2018.cnblogs.com/blog/425762/201805/425762-20180523193350024-1394121124.png) 



### 20、看图写结果：

![](https://images2018.cnblogs.com/blog/425762/201805/425762-20180523193402254-925709250.png) 



### 21、看图写结果：

![](https://images2018.cnblogs.com/blog/425762/201805/425762-20180523193412085-688600397.png) 



### 22、看图写结果：

![](https://images2018.cnblogs.com/blog/425762/201805/425762-20180523193421487-536908496.png) 



### 23、看图写结果：

![](https://images2018.cnblogs.com/blog/425762/201805/425762-20180523193433388-1947519928.png) 



### 24、django、flask、tornado框架的比较？

### 25、什么是wsgi？

### 26、django请求的生命周期？

### 27、列举django的内置组件？

### 28、列举django中间件的5个方法？以及django中间件的应用场景？

### 29、简述什么是FBV和CBV？

### 30、django的request对象是在什么时候创建的？

### 31、如何给CBV的程序添加装饰器？

### 32、列举django orm 中所有的方法（QuerySet对象的所有方法）

### 33、only和defer的区别？

### 34、select_related和prefetch_related的区别？

### 35、filter和exclude的区别？

### 36、列举django orm中三种能写sql语句的方法。

### 37、django orm 中如何设置读写分离？

### 38、F和Q的作用?

### 39、values和values_list的区别？

### 40、如何使用django orm批量创建数据？

### 41、django的Form和ModeForm的作用？

### 42、django的Form组件中，如果字段中包含choices参数，请使用两种方式实现数据源实时更新。

### 43、django的Model中的ForeignKey字段中的on_delete参数有什么作用？

### 44、django中csrf的实现机制？

### 45、django如何实现websocket？

### 46、基于django使用ajax发送post请求时，都可以使用哪种方法携带csrf token？

### 47、django中如何实现orm表中添加数据时创建一条日志记录。

### 48、django缓存如何设置？

### 49、django的缓存能使用redis吗？如果可以的话，如何配置？

### 50、django路由系统中name的作用？

### 51、django的模板中filter和simple_tag的区别？

### 52、django-debug-toolbar的作用？

### 53、django中如何实现单元测试？

### 54、解释orm中 db first 和 code first的含义？

### 55、django中如何根据数据库表生成model中的类？

### 56、使用orm和原生sql的优缺点？

### 57、简述MVC和MTV

### 58、django的contenttype组件的作用？

### 59、谈谈你对restfull 规范的认识？

### 60、接口的幂等性是什么意思？

### 61、什么是RPC？

### 62、Http和Https的区别？

### 63、为什么要使用django rest framework框架？

### 64、django rest framework框架中都有那些组件？

### 65、django rest framework框架中的视图都可以继承哪些类？

### 66、简述 django rest framework框架的认证流程。

### 67、django rest framework如何实现的用户访问频率控制？

### 68、Flask框架的优势？

### 69、Flask框架依赖组件？

### 70、Flask蓝图的作用？

### 71、列举使用过的Flask第三方组件？

### 72、简述Flask上下文管理流程?

### 73、Flask中的g的作用？

### 74、Flask中上下文管理主要涉及到了那些相关的类？并描述类主要作用？

### 75、为什么要Flask把Local对象中的的值stack 维护成一个列表？

### 76、Flask中多app应用是怎么完成？

### 77、在Flask中实现WebSocket需要什么组件？

### 78、wtforms组件的作用？

### 79、Flask框架默认session处理机制？

### 80、解释Flask框架中的Local对象和threading.local对象的区别？

### 81、Flask中 blinker 是什么？

### 82、SQLAlchemy中的 session和scoped_session 的区别？

### 83、SQLAlchemy如何执行原生SQL？

### 84、ORM的实现原理？

### 85、DBUtils模块的作用？

### 86、以下SQLAlchemy的字段是否正确？如果不正确请更正：

```
 from datetime import datetime

 from sqlalchemy.ext.declarative

 import declarative_base

 from sqlalchemy import Column, Integer, String, DateTime


 Base = declarative_base()

 class UserInfo(Base):

     __tablename__ = 'userinfo'

     id = Column(Integer, primary_key=True, autoincrement=True)

     name = Column(String(64), unique=True)

     ctime = Column(DateTime, default=datetime.now())

 ```

### 87、SQLAchemy中如何为表设置引擎和字符编码？

### 88、SQLAchemy中如何设置联合唯一索引？

### 89、简述Tornado框架的特点。

### 90、简述Tornado框架中Future对象的作用？

### 91、Tornado框架中如何编写WebSocket程序？

### 92、Tornado中静态文件是如何处理的？如： <link href="{{static_url("commons.css")}}" rel="stylesheet" />

### 93、Tornado操作MySQL使用的模块？

### 94、Tornado操作redis使用的模块？

### 95、简述Tornado框架的适用场景？

### 96、git常见命令作用：

### 97、简述以下git中stash命令作用以及相关其他命令。

### 98、git 中 merge 和 rebase命令 的区别。

### 99、公司如何基于git做的协同开发？

### 100、如何基于git实现代码review？

### 101、git如何实现v1.0 、v2.0 等版本的管理？

### 102、什么是gitlab？

### 103、github和gitlab的区别？

### 104、如何为github上牛逼的开源项目贡献代码？

### 105、git中 .gitignore文件的作用?

### 106、什么是敏捷开发？

### 107、简述 jenkins 工具的作用?

### 108、公司如何实现代码发布？

### 109、简述 RabbitMQ、Kafka、ZeroMQ的区别？

### 110、RabbitMQ如何在消费者获取任务后未处理完前就挂掉时，保证数据不丢失？

### 111、RabbitMQ如何对消息做持久化？

### 112、RabbitMQ如何控制消息被消费的顺序？

### 113、以下RabbitMQ的exchange type分别代表什么意思？如：fanout、direct、topic。

### 114、简述 celery 是什么以及应用场景？

### 115、简述celery运行机制。

### 116、celery如何实现定时任务？

### 117、简述 celery多任务结构目录？

### 118、celery中装饰器 @app.task 和 @shared_task的区别？

### 119、简述 requests模块的作用及基本使用？

### 120、简述 beautifulsoup模块的作用及基本使用？

### 121、简述 seleninu模块的作用及基本使用?

### 122、scrapy框架中各组件的工作流程？

### 123、在scrapy框架中如何设置代理（两种方法）？

### 124、scrapy框架中如何实现大文件的下载？

### 125、scrapy中如何实现限速？

### 126、scrapy中如何实现暂定爬虫？

### 127、scrapy中如何进行自定制命令？

### 128、scrapy中如何实现的记录爬虫的深度？

### 129、scrapy中的pipelines工作原理？

### 130、scrapy的pipelines如何丢弃一个item对象？

### 131、简述scrapy中爬虫中间件和下载中间件的作用？

### 132、scrapy-redis组件的作用？

### 133、scrapy-redis组件中如何实现的任务的去重？

### 134、scrapy-redis的调度器如何实现任务的深度优先和广度优先？

### 135、简述 vitualenv 及应用场景?

### 136、简述 pipreqs 及应用场景？

### 137、在Python中使用过什么代码检查工具？

### 138、简述 saltstack、ansible、fabric、puppet工具的作用？

### 139、B Tree和B+ Tree的区别？

### 140、请列举常见排序并通过代码实现任意三种。

### 141、请列举常见查找并通过代码实现任意三种。

### 142、请列举你熟悉的设计模式？

### 143、有没有刷过leetcode？

### 144、列举熟悉的的Linux命令。

### 145、公司线上服务器是什么系统？

### 146、解释 PV、UV 的含义？

### 147、解释 QPS的含义？

### 148、uwsgi和wsgi的区别？

### 149、supervisor的作用？

### 150、什么是反向代理？

### 151、简述SSH的整个过程。

### 152、有问题都去那些找解决方案？

### 153、是否有关注什么技术类的公众号？

### 154、最近在研究什么新技术？

### 155、是否了解过领域驱动模型？
  

### 统计：80 + 34 + 46 + 155 = 315题

##  声明致谢：

### 本文来自微信公众号【Python开发者】，该公众号又转载于博客【路飞学城作者】所写的[不吹不擂，你想要的Python面试都在这里了【315+道题】](https://www.cnblogs.com/wupeiqi/p/9078770.html)

### 长叹息以掩涕兮,哀编程之多艰！希望各位同学砥砺前行，勿气勿馁。