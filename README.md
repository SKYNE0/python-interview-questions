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

当然，不管我们通过什么渠道，方式开始学习Python，我们都应当坚持下去。
```

### 2、通过什么途径学习的Python？

##### 参考下面两篇知乎文章：
##### [1,关于 Python 的经典入门书籍有哪些？](https://www.zhihu.com/question/19593179)
##### [2,怎么用最短时间高效而踏实地学习 Python？](https://www.zhihu.com/question/28530832)
##### 自己说：Python确实是门语法简洁优美，入门简单的语言，但如何写出极具Pythonic风格的代码，是需要耐心学习，刻苦练习的，
##### 如果有其他语言基础的话，自己觉得看书的效率更高，当然，通过视频当然更适合理解晦涩难懂的概念，虽然Python中并不多。


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
C语言的语法限制不太严格，对变量的类型约束不严格，影响程序的安全性，对数组下标越界不作检查等。从应用的角度，
C语言比其他高级语言较难掌握。也就是说，对用C语言的人，要求对程序设计更熟练一些。


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

翻译的方式有两种，一个是编译，一个是解释。两种方式只是翻译的时间不同。编译型语言写的程序执行之前，
需要一个专门的编译过程，把程序编译成为机器语言的文件，比如exe文件，
以后要运行的话就不用重新翻译了，直接使用编译的结果就行了（exe文件），因为翻译只做了一次，
运行时不需要翻译，所以编译型语言的程序执行效率高。

解释则不同，解释性语言的程序不需要编译，省了道工序，解释性语言在运行程序的时候才翻译，
比如解释性basic语言，专门有一个解释器能够直接执行basic程序，
每个语句都是执行的时候才翻译。这样解释性语言每执行一次就要翻译一次，效率比较低。

编译型与解释型，两者各有利弊。前者由于程序执行速度快，同等条件下对系统要求较低，
因此像开发操作系统、大型应用程序、数据库系统等时都采用它，像C/C++、Pascal/Object Pascal（Delphi）等都是编译语言，
而一些网页脚本、服务器脚本及辅助开发接口这样的对速度要求不高、
对不同系统平台间的兼容性有一定要求的程序则通常使用解释性语言，如JavaScript、VBScript、Perl、Python、Ruby、MATLAB 等等。
```
##### 详细介绍：
##### [编译型与解释型、动态语言与静态语言、强类型语言与弱类型语言的区别](https://juejin.im/entry/58918ef0128fe1006c92e1a4)
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

PyPy是另一个Python解释器，它的目标是执行速度。PyPy采用JIT技术，对Python代码进行动态编译（注意不是解释），
所以可以显著提高Python代码的执行速度。绝大部分Python代码都可以在PyPy下运行，
但是PyPy和CPython有一些是不同的，这就导致相同的Python代码在两种解释器下执行可能会有不同的结果。
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
代码规范主要是以下几点：

一 代码编排

二 文档编排

三 空格的使用

四 注释

五 文档描述

六 命名规范

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
最早只有127个字母被编码到计算机里，也就是大小写英文字母、数字和一些符号，这个编码表被称为ASCII编码，

比如大写字母A的编码是65，小写字母z的编码是122。

但是要处理中文显然一个字节是不够的，至少需要两个字节，而且还不能和ASCII编码冲突，

所以，中国制定了GB2312编码，用来把中文编进去。

你可以想得到的是，全世界有上百种语言，日本把日文编到Shift_JIS里，韩国把韩文编到Euc-kr里，

各国有各国的标准，就会不可避免地出现冲突，

结果就是，在多语言混合的文本中，显示出来会有乱码。

因此，Unicode应运而生。Unicode把所有语言都统一到一套编码里，这样就不会再有乱码问题了。

Unicode标准也在不断发展，但最常用的是用两个字节表示一个字符（如果要用到非常偏僻的字符，就需要4个字节）。

现代操作系统和大多数编程语言都直接支持Unicode。新的问题又出现了：如果统一成Unicode编码，乱码问题从此消失了。

但是，如果你写的文本基本上全部是英文的话，用Unicode编码比ASCII编码需要多一倍的存储空间，在存储和传输上就十分不划算。

所以，本着节约的精神，又出现了把Unicode编码转化为“可变长编码”的UTF-8编码。

UTF-8编码把一个Unicode字符根据不同的数字大小编码成1-6个字节，

常用的英文字母被编码成1个字节，汉字通常是3个字节，只有很生僻的字符才会被编码成4-6个字节。

如果你要传输的文本包含大量英文字符，用UTF-8编码就能节省空间。

UTF-8编码有一个额外的好处，就是ASCII编码实际上可以被看成是UTF-8编码的一部分，

所以，大量只支持ASCII编码的历史遗留软件可以在UTF-8编码下继续工作。
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

用机器语言编写程序，编程人员要首先熟记所用计算机的全部指令代码和代码的涵义。手编程序时，
程序员得自己处理每条指令和每一数据的存储分配和输入输出，
还得记住编程过程中每步所使用的工作单元处在何种状态。这是一件十分繁琐的工作，
编写程序花费的时间往往是实际运行时间的几十倍或几百倍。
而且，编出的程序全是些0和1的指令代码，直观性差，还容易出错。
现在，除了计算机生产厂家的专业人员外，绝大多数的程序员已经不再去学习机器语言了。

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
     一、python2  的代码混乱 重复较多 冗余  因为当时来编写的人有C 语言的大牛 和 java的大牛等各种大神 
	 所以里面都含有各种语言的影子
     python3  经过龟叔的一个暑假的整理 终于在2008年11月 统一了代码  源码规范 清晰 简单优美。 

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
只有一种整数类型int，大多数情况下，它很像Python 2里的长整型。由于已经不存在两种类型的整数，
所以就没有必要使用特殊的语法去区别他们。

Notes  	Python 2 	         Python 3

① 	x =1000000000000L 	  x =1000000000000

② 	x =0xFFFFFFFFFFFFL 	  x =0xFFFFFFFFFFFF

③ 	    long(x) 	            int(x)

④ 	  type(x)is long 	     type(x)is int

⑤ 	isinstance(x,long) 	isinstance(x,int)

在Python 2里的十进制长整型在Python 3里被替换为十进制的普通整数。
在Python 2里的十六进制长整型在Python 3里被替换为十六进制的普通整数。
在Python 3里，由于长整型已经不存在了，自然原来的long()函数也没有了。
为了强制转换一个变量到整型，可以使用int()函数。
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
虽然lambda函数看起来只能写一行，却不等同于C或C++的内联函数，
后者的目的是调用小函数时不占用栈内存从而增加运行效率

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
= 赋值：数据完全共享（=赋值是在内存中指向同一个对象，如果是可变(mutable)类型，
比如列表，修改其中一个，另一个必定改变， 
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

PyObject是每个对象必有的内容，其中ob_refcnt就是做为引用计数。
当一个对象有新的引用时，它的ob_refcnt就会增加，
当引用它的对象被删除，它的ob_refcnt就会减少.
引用计数为0时，该对象生命就结束了。

优点:

    简单
    实时性

缺点:

    维护引用计数消耗资源
    循环引用

2 标记-清除机制

基本思路是先按需分配，等到没有空闲内存的时候从寄存器和程序栈上的引用出发，
遍历以对象为节点、以引用为边构成的图，把所有可以访问到的对象打上标记，
然后清扫一遍内存空间，把所有没标记的对象释放。
3 分代技术

分代回收的整体思想是：将系统中的所有内存块根据其存活时间划分为不同的集合，每个集合就成为一个“代”，
垃圾收集频率随着“代”的存活时间的增大而减小，存活时间通常利用经过几次垃圾回收来度量。

Python默认定义了三代对象集合，索引数越大，对象存活时间越长。

举例： 当某些内存块M经过了3次垃圾收集的清洗之后还存活时，我们就将内存块M划到一个集合A中去，
而新分配的内存都划分到集合B中去。
当垃圾收集开始工作时，大多数情况都只对集合B进行垃圾回收，
而对集合A进行垃圾回收要隔相当长一段时间后才进行，
这就使得垃圾收集机制需要处理的内存少了，效率自然就提高了。
在这个过程中，集合B中的某些内存块由于存活时间长而会被转移到集合A中，
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
```
filter(function, sequence)：对sequence中的item依次执行function(item)，将执行结果为True的item组成一个List/String/Tuple（取决于sequence的类型）。

filter(function or None, sequence) -> list, tuple, or string：入参为函数和列表/元组/字符串，返回值为item列表/元组/字符串。

map(function, sequence) ：对sequence中的item依次执行function(item)，将执行结果function(item)组成一个List返回。

map(function, sequence[, sequence, ...]) -> list：入参是为函数和列表/元组/字符串，返回值为function(item)列表。

reduce(function, sequence, starting_value)：对sequence中的item顺序迭代调用function，如果有starting_value，还可以作为初始值调用。function接收的参数个数只能为2，先把sequence中第一个值和第二个值当参数传给function，再把function的返回值和第三个值当参数传给function，然后只返回一个结果。

reduce(function, sequence[, initial]) -> value：入参是为函数和列表/元组/字符串和初始值，返回值为数值。
```
##### 参考阅读：[不得不知的python高阶函数（Map、Reduce、Filter）](https://blog.csdn.net/u010541307/article/details/53189969)

### 34、一行代码实现9*9乘法表?
```
print("\n".join("\t".join(["%s*%s=%s" % (x, y, x * y) for y in range(1, x + 1)]) for x in range(1, 10)))
自己说：看起来不是那么好理解。
```
### 35、如何安装第三方模块？以及用过哪些第三方模块？
##### 参考阅读：[安装第三方模块](https://www.liaoxuefeng.com/wiki/001374738125095c955c1e6d8bb493182103fac9270762a000/0013868200214529634268c5b3b45b3a3ba1cd81a251a3b000)

### 36、至少列举8个常用模块都有哪些？
```
os , sys, time, random, logging
```
### 37、re的match和search区别？
```
re模块中match(pattern,string[,flags]),检查string的开头是否与pattern匹配。

re模块中research(pattern,string[,flags]),在string搜索pattern的第一个匹配值。
```

### 38、什么是正则的贪婪匹配？
```
如：String str="abcaxc";

Patter p="ab*c";

贪婪匹配:正则表达式一般趋向于最大长度匹配，也就是所谓的贪婪匹配。如上面使用模式p匹配字符串str，结果就是匹配到：abcaxc(ab*c)。
非贪婪匹配：就是匹配到结果就好，就少的匹配字符。如上面使用模式p匹配字符串str，结果就是匹配到：abc(ab*c)。

编程中如何区分两种模式

默认是贪婪模式；在量词后面直接加上一个问号？就是非贪婪模式。
```
##### 参考阅读：[Python 正则表达式之三：贪婪](https://juejin.im/entry/58b6c3b98d6d810065225d1d)

### 39、求结果： 
###  a： [ i % 2 for i in range(10) ] 
###  b： ( i % 2 for i in range(10) )
```
a: [0, 1, 0, 1, 0, 1, 0, 1, 0, 1]
b: <generator object <genexpr> at 0x011A3E40>
自己说：对于a就是个列表表达式，b则是个元组生成器
```
##### 参考阅读：[python之字典、列表、元组生成器的使用](https://www.cnblogs.com/cwp-bg/p/9041319.html)

### 40、求结果： 
###  a. 1 or 2 
###  b. 1 and 2 
###  c. 1 < (2==2) 
###  d. 1 < 2 == 2
```
1
2
False
True
```
##### 参考阅读：[python中and-or语法](https://blog.csdn.net/permike/article/details/52311211)

### 41、def func(a,b=[]) 这种写法有什么坑？
```
Pycharm的语法警告：
Default argument value is mutable less... (Ctrl+F1) 
This inspection detects when a mutable value as list or dictionary is detected in a default value for an argument.
Default argument values are evaluated only once at function definition time, which means that 
modifying the default value of the argument will affect all subsequent calls of the function
最后一句的翻译：这意味着修改参数的默认值将影响函数的所有后续调用
网友解释：
b=[] 不是空的意思 就是默认创建了一个长度为0的list 这个在定义函数的时候就创建了 
又因为创建的b是一个变量 而且是不可变的对象 
也就是始终指向同一地址 所以每次调用函数得到的b都会改变
所以：建议b的默认值为None
```

### 42、如何实现 “1,2,3” 变成 [‘1’,’2’,’3’] ?
```
astring = “1,2,3”
list(astring.split(','))
```

### 43、如何实现[‘1’,’2’,’3’]变成[1,2,3] ?
```
map(int, [‘1’,’2’,’3’])
```
### 44、比较： a = [1,2,3] 和 b = [(1),(2),(3) ] 以及 b = [(1,),(2,),(3,) ] 的区别？
```
自己说：能力有限，但可以看出，a， b相同，a, b都是list,所包含的元素都为int, 最后边的b包含的元素是tuple
```

### 45、如何用一行代码生成[1,4,9,16,25,36,49,64,81,100] ?
```
[x*x for x in range(1, 11)]
```

### 46、一行代码实现删除列表中重复的值 ?
```
alist = [6,9,3,6,5,4,78,5,4,4,4]
list(set(alsit))
```

### 47、如何在函数中设置一个全局变量 ?
```
global var
```
### 48、logging模块的作用？以及应用场景？
```
Python的logging模块提供了通用的日志系统，可以方便第三方模块或者是应用使用。
这个模块提供不同的日志级别，并可以采用不同的方式记录日志，
比如文件，HTTP GET/POST，SMTP，Socket等，甚至可以自己实现具体的日志记录方式。

日志是一种可以追踪某些软件运行时所发生事件的方法。软件开发人员可以向他们的代码中调用日志记录相关的方法来表明发生了某些事情。
一个事件可以用一个可包含可选变量数据的消息来描述。此外，事件也有重要性的概念，这个重要性也可以被称为严重性级别（level）。

1.日志的作用

通过log的分析，可以方便用户了解系统或软件、应用的运行情况；如果你的应用log足够丰富，
也可以分析以往用户的操作行为、类型喜好、地域分布或其他更多信息；如果一个应用的log同时也分了多个级别，
那么可以很轻易地分析得到该应用的健康状况，及时发现问题并快速定位、解决问题，补救损失。
简单来讲就是，我们通过记录和分析日志可以了解一个系统或软件程序运行情况是否正常，
也可以在应用程序出现故障时快速定位问题。比如，做运维的同学，在接收到报警或各种问题反馈后，
进行问题排查时通常都会先去看各种日志，大部分问题都可以在日志中找到答案。再比如，做开发的同学，
可以通过IDE控制台上输出的各种日志进行程序调试。对于运维老司机或者有经验的开发人员，
可以快速的通过日志定位到问题的根源。可见，日志的重要性不可小觑。日志的作用可以简单总结为以下3点：

    程序调试
    了解软件程序运行情况，是否正常
    软件程序运行故障分析与问题定位

如果应用的日志信息足够详细和丰富，还可以用来做用户行为分析，
如：分析用户的操作行为、类型洗好、地域分布以及其它更多的信息，
由此可以实现改进业务、提高商业利益。
```
##### 参考阅读：[ Python之logging模块](https://www.cnblogs.com/Richardzhu/p/5303887.html)

### 49、请用代码解答实现stack 。
```
Python: 3.x

class stack(object):


	def __init__(self):
		self.items = []
		
	def isEmpty(self):
		return self.items == []
	
	def push(self, item):
		self.items.append(item)
	
	def pop(self):
		return self.items.pop()
		
	def peek(self):
		return self.items[-1]
	
	def size(self):
		return len(self.items)
	
```

### 50、常用字符串格式化哪几种？
```
1.最方便的
    print 'hello %s and %s' % ('df', 'another df')  

但是，有时候，我们有很多的参数要进行格式化，这个时候，一个一个一一对应就有点麻烦了，于是就有了第二种，字典形式的。上面那种是tuple形式的。

2.最好用的
    print 'hello %(first)s and %(second)s' % {'first': 'df', 'second': 'another df'}  

这种字典形式的字符串格式化方法，有一个最大的好处就是，字典这个东西可以和json文件相互转换，所以，当配置文件使用字符串设置的时候，就显得相当方便。

3.最先进的
    print 'hello {first} and {second}'.format(first='df', second='another df')  
```
##### 自己说：内容来自[python的三种字符串格式化方法](https://blog.csdn.net/qtlyx/article/details/77102851)
##### 参考阅读：[Python字符串格式化的两种方式](https://www.cnblogs.com/hifelix/p/5881748.html)

### 51、简述 生成器、迭代器、可迭代对象 以及应用场景？
```
一：语法糖
从字面上看应该是一种语法。“糖”，可以理解为简单、简洁。其实我们也已经意识到，
没有这些被称为“语法糖”的语法，我们也能实现相应的功能，而 “语法糖”使我们可以更加简洁、快速的实现这些功能。
只是Python解释器会把这些特定格式的语法翻译成原本那样复杂的代码逻辑而已，没有什么太高深的东西。
像列表推导式，字典推导式，元组生成器，以及生成器，迭代器应该都是语法糖。

二：生成器（generator）
生成器是构造迭代器的最简单有力的工具，与普通函数不同的只有在返回一个值的时候使用yield来替代return，
然后yield会自动构建好next()和iter()。

三：迭代器（iterator）
迭代器是通过next()来实现的，每调用一次他就会返回下一个元素，当没有下一个元素的时候返回一个StopIteration异常，
所以实际上定义了这个方法的都算是迭代器。

四：可迭代对象（iterable）
Python中经常使用for来对某个对象进行遍历，此时被遍历的这个对象就是可迭代对象，
像常见的list,tuple都是。如果给一个准确的定义的话，就是只要它定义了可以返回一个迭代器的__iter__方法，
或者定义了可以支持下标索引的__getitem__方法(这些双下划线方法会在其他章节中全面解释)，
那么它就是一个可迭代对象。
值得一提的是，这就是Python中的多态，而且Python非常推崇鸭子类型。
```
##### 参考阅读：[Python迭代器，可迭代对象，生成器](https://blog.csdn.net/doublehhcc/article/details/78756400)

### 52、用Python实现一个二分查找的函数。
```
def binary_search(alist, key)
	
	low, high = 0, 0
	mid = len(alist) - 1
	time = 0
	
	while low < high:
		time += 1
		mid = (low + high) // 2
		if alist[mid] < key:
			low = mid + 1
		elif alist[mid] > key:
			high = mid - 1
		else:
			print("Search {} times!\n".format(time))
			return mid
	
	print("No Search {} times!\n".format(time))
	return False
```

### 53、谈谈你对闭包的理解？
```
闭包需要满足的条件：

    1. 必须有一个内嵌函数
    2. 内嵌函数必须引用外部函数中的变量
    3. 外部函数的返回值必须是内嵌函数

闭包的概念不太好理解，自己也似懂非懂。请参考下面的阅读。
```
##### 参考阅读：[闭包_百度百科](https://baike.baidu.com/item/%E9%97%AD%E5%8C%85/10908873?fr=aladdin)
##### [Python 中的闭包 - Python - 伯乐在线](http://python.jobbole.com/82296/)
##### [谈谈自己的理解:python中闭包，闭包的实质 - 稀里糊涂林老冷 - 博客园](https://www.cnblogs.com/Lin-Yi/p/7305364.html)

### 54、os和sys模块的作用？
```
两者的主要区别：
os模块负责程序与操作系统的交互，提供了访问操作系统底层的接口，
sys模块负责程序与Python解释器的交互，提供了一系列的函数和变量，用于操控python的运行时环境。
```
##### 参考阅读：[os和sys模块-君醉-博客园](https://www.cnblogs.com/pycode/p/sysos.html)

### 55、如何生成一个随机数？
```
Python中使用Random模块来生成随机数
常用的方法有：.randint(), .random(), .randrange(), .sample(), .seed(), .uniform()
```
### 56、如何使用python删除一个文件？
```
使用os模块中的remove方法，注意判断文件是否存在，是否具有权限。
```

### 57、谈谈你对面向对象的理解？
```
    面向对象编程，即OOP，是一种编程范式，满足面向对象编程的语言，
	一般会提供类、封装、继承等语法和概念来辅助我们进行面向对象编程。

    面向对象是基于万物皆对象这个哲学观点. 所谓的面向对象就是将我们的程序模块化，对象化，
	把具体事物的特性属性和通过这些属性来实现一些动作的具体方法放到一个类里面

    面向对象的三大特征 继承，封装，多态

    一 继承
        继承概念：一个类继承另一个类，则称继承的类为子类，被继承的类为父类。
        目的：实现代码的复用。
        理解：子类与父类的关系并不是日常生活中的父子关系，子类与父类而是一种特殊化与一般化的关系，
		是is-a的关系，子类是父类更加详细的分类。如 class dog 继承于 animal,
		就可以理解为dog is a animal.注意设计继承的时候.
		
        结果：继承后子类自动拥有了父类的属性和方法，子类可以写自己特有的属性和方法，
		目的是实现功能的扩展，子类也可以复写父类的方法即方法的重写。

    二 封装

        概念：封装也称为信息隐藏，是指利用抽象数据类型将数据和基于数据的操作封装在一起，
		使其构成一个不可分割的独立实体，数据被保护在抽象数据类型的内部，尽可能地隐藏内部的细节，
		只保留一些对外接口使之与外部发生联系。
		系统的其他部分只有通过包裹在数据外面的被授权的操作来与这个抽象数据类型交流与交互。
		也就是说，用户无需知道对象内部方法的实现细节，但可以根据对象提供的外部接口(对象名和参数)访问该对象。

        好处：(1)实现了专业的分工。将能实现某一特定功能的代码封装成一个独立的实体后，
		各程序员可以在需要的时候调用，从而实现了专业的分工。
		(2)隐藏信 息，实现细节。通过控制访问权限可以将可以将不想让客户端程序员看到的信息隐藏起来，
		如某客户的银行的密码需要保密，只能对该客户开发权限。

    三、多态
        概念：相同的事物，调用其相同的方法，参数也相同时，但表现的行为却不同。
        理解：子类以父类的身份出现，但做事情时还是以自己的方法实现。
		子类以父类的身份出现需要向上转型(upcast)，其中向上转型是由JVM自动实现的， 
		是安全的，但向下转型(downcast)是不安全的，需要强制转换。
		子类以父类的身份出现时自己特有的属性和方法将不能使用。

    “面向过程”和“面向对象”的区别
        面向过程就是分析出解决问题所需要的步骤，然后用函数把这些步骤一步一步实现，
		使用的时候一个一个依次调用就可以了；面向对象是把构成问题事务分解成各个对象，
		建立对象的目的不是为了完成一个步骤，而是为了描叙某个事物在整个解决问题的步骤中的行为
		。 
        可以拿生活中的实例来理解面向过程与面向对象，例如五子棋，面向过程的设计思路就是首先分析问题的步骤：
            1、开始游戏，2、黑子先走，3、绘制画面，4、判断输赢，5、轮到白子，6、绘制画面，7、判断输赢，
			8、返回步骤 2，9、输出最后结果。把上面每个步骤用不同的方法来实现。
             
            如果是面向对象的设计思想来解决问题。面向对象的设计则是从另外的思路来 解决问题。
			整个五子棋可以分为
			1、黑白双方，这两方的行为是一模一样的，
			2、棋盘系统，负责绘制画面，
			3、规则系统，负责判定诸如犯规、输赢等。第一类对 象（玩家对象）负责接受用户输入，
			并告知第二类对象（棋盘对象）棋子布局的变化，棋盘对象接收到了棋子的变化就要负责在屏幕上面显示出这种变化，
			同时利用 第三类对象（规则系统）来对棋局进行判定。
```
##### 参考阅读：[我对面向对象的理解-往事亦如风](https://www.cnblogs.com/ldnh/p/5475069.html)

### 58、Python面向对象中的继承有什么特点？
```
自己简单知道Pytho能多重继承，即继承多个父类，由此也存在MRO（方法解析顺序）问题，多重继承往往与super（）方法一起提及 
```
##### 参考阅读：[Python继承概念的这些优缺点你知道吗？](http://developer.51cto.com/art/201802/566029.htm)

### 59、面向对象深度优先和广度优先是什么？
```
这个涉及到经典类与新式类中的MRO（方法解析顺序）问题，请看下面的参考阅读。
```
##### 参考阅读：[你真的理解Python中MRO算法吗？](http://python.jobbole.com/85685/)

### 60、面向对象中super的作用？
```
super() 函数是用于调用父类(超类)的一个方法。

super 是用来解决多重继承问题的，直接用类名调用父类方法在使用单继承的时候没问题，
但是如果使用多继承，会涉及到查找顺序（MRO）、重复调用（钻石继承）等种种问题。
```
##### 参考阅读：[Python super()函数](http://www.runoob.com/python/python-func-super.html)
##### [Python: 你不知道的 super](http://python.jobbole.com/86787/)

### 61、是否使用过functools中的函数？其作用是什么？
```
这个自己也不太清楚，请参考下面的参考阅读。
```
##### [Python标准模块--functools](https://www.cnblogs.com/zhbzz2007/p/6001827.html)
##### [Python-进阶-functools模块小结](http://wklken.me/posts/2013/08/18/python-extra-functools.html)

### 62、列举面向对象中带爽下划线的特殊方法，如：__new__、__init__
```
_init__(self,...) 、__del__(self) 、__call__(self, *args) 、__str__(self, 方法)
__add__、__dic__、__getitem__、__setitem__、__delitem__、__iter__
```
##### 参考阅读：[Python面向对象5：特殊方法](https://blog.csdn.net/PbGc396Dwxjb77F2je/article/details/78890715)

### 63、如何判断是函数还是方法？
```
通过type()可以知道对象所属的类型，函数是<class 'function'>，方法是<class 'method'>
```

### 64、静态方法和类方法区别？
```
实例方法只能被实例对象调用，静态方法(由@staticmethod装饰的方法)、类方法(由@classmethod装饰的方法)，可以被类或类的实例对象调用。
实例方法，第一个参数必须要默认传实例对象，一般习惯用self。
静态方法，参数没有要求。
类方法，第一个参数必须要默认传类，一般习惯用cls。
```
##### 参考阅读：[python类的静态方法和类方法区别](https://www.jianshu.com/p/212b6fdb2c50)

### 65、列举面向对象中的特殊成员以及应用场景?
```
1.__doc__ ：打印类的描述信息

2.__module__:表示当前操作的对象在那个模块

3.__class__：表示当前操作的对象的类是什么

4. __init__ ：构造方法，通过类创建对象时，自动触发执行

5.__del__:析构方法，当对象在内存中被释放时，自动触发执行

6.__call__:对象后面加括号，触发执行

7.__dict__:查看类或对象中的所有成员

8.__str__：如果一个类中定义了__str__方法，那么在打印 对象 时，默认输出该方法的返回值

9.__getitem__、__setitem__、__delitem__:

注：用于索引操作，如字典。以上分别表示获取、设置、删除数据

10.__new__\__metaclass__ *（自定义类）

__new__:是用来创建实例的，对类实例化之前进行定制，可以用到。

__metaclass__：定义一个类如何被创建
```
##### 参考阅读：[Python 类的特殊成员方法](https://www.cnblogs.com/bearkchan/p/8267749.html)

### 66、1、2、3、4、5 能组成多少个互不相同且无重复的三位数?
```
5 X 5 X 5 = 125
```

### 67、什么是反射？以及应用场景？
```
解释一： python的反射，它的核心本质其实就是利用字符串的形式去对象（模块）中操作（查找/获取/删除/添加）成员，一种基于字符串的事件驱动。

解释二: 需要执行对象里的某个方法，或需要调用对象中的某个变量，但是由于种种原因我们无法确定这个方法或变量是否存在，
这是我们需要用一个特殊的方法或机制要访问和操作这个未知的方法或变量，这中机制就称之为反射。

几个重要方法：

hasattr: 判断对象中是否有这个方法或变量

getattr: 获取对象中的方法或变量的内存地址

setattr: 为对象添加变量或方法

delattr: 删除对象中的变量。注意：不能用于删除方法
```
##### 参考阅读：[python的反射机制](https://www.cnblogs.com/Guido-admirers/p/6206212.html)
##### [Python-反射的用法](https://blog.csdn.net/y472360651/article/details/73277957)

### 68、metaclass作用？以及应用场景？
```
这个很难理解，自己也不太懂。请参考下面的文章。
```
##### 参考阅读：[使用元类 - 廖雪峰的官方网站](https://www.liaoxuefeng.com/wiki/001374738125095c955c1e6d8bb493182103fac9270762a000/001386820064557c69858840b4c48d2b8411bc2ea9099ba000)
##### [深刻理解Python中的元类(metaclass)](http://blog.jobbole.com/21351/)

### 69、用尽量多的方法实现单例模式。
```
? 单例模式是一种常用的软件设计模式。在它的核心结构中只包含一个被称为单例类的特殊类。
通过单例模式可以保证系统中一个类只有一个实例而且该实例易于外界访问，
从而方便对实例个数的控制并节约系统资源。
如果希望在系统中某个类的对象只能存在一个，单例模式是最好的解决方案。

__new__()在__init__()之前被调用，用于生成实例对象。
利用这个方法和类的属性的特点可以实现设计模式的单例模式。
单例模式是指创建唯一对象，

1 使用__new__方法

class Singleton(object):
    def __new__(cls, *args, **kw):
        if not hasattr(cls, '_instance'):
            orig = super(Singleton, cls)
            cls._instance = orig.__new__(cls, *args, **kw)
        return cls._instance

class MyClass(Singleton):
    a = 1

2 共享属性

创建实例时把所有实例的__dict__指向同一个字典,这样它们具有相同的属性和方法.

class Borg(object):
    _state = {}
    def __new__(cls, *args, **kw):
        ob = super(Borg, cls).__new__(cls, *args, **kw)
        ob.__dict__ = cls._state
        return ob

class MyClass2(Borg):
    a = 1

3 装饰器版本

def singleton(cls):
    instances = {}
    def getinstance(*args, **kw):
        if cls not in instances:
            instances[cls] = cls(*args, **kw)
        return instances[cls]
    return getinstance

@singleton
class MyClass:
  ...

4 import方法

作为python的模块是天然的单例模式

# mysingleton.py
class My_Singleton(object):
    def foo(self):
        pass

my_singleton = My_Singleton()

# to use
from mysingleton import my_singleton

my_singleton.foo()
```
##### 参考阅读：[Python 中的单例模式](http://python.jobbole.com/87294/)

### 70、装饰器的写法以及应用场景。
```
装饰器是一个很著名的设计模式，经常被用于有切面需求的场景，
较为经典的有插入日志、性能测试、事务处理等。装饰器是解决这类问题的绝佳设计，
有了装饰器，我们就可以抽离出大量函数中与函数功能本身无关的雷同代码并继续重用。
概括的讲，装饰器的作用就是为已经存在的对象添加额外的功能。

def decorator(func):
	def wapper(*args, **kwargs):
		print("This is a defcorator!")
		reture func(*args, **kwargs)
	return wapper
```
##### 参考阅读：[Python中如何在一个函数中加入多个装饰器? ](https://taizilongxu.gitbooks.io/stackoverflow-about-python/content/3/README.html)

### 71、异常处理写法以及如何主动跑出异常（应用场景）
```
try:
	<语句>        #运行别的代码
except <名字>：
	<语句>        #如果在try部份引发了'name'异常
except <名字>，<数据>:
	<语句>        #如果引发了'name'异常，获得附加的数据
else:
	<语句>        #如果没有异常发生
finally:
	<语句>        #语句无论是否发生异常都将执行最后的代码。


raise语句自动触发异常

raise语法格式如下：

raise [Exception [, args [, traceback]]]

语句中 Exception 是异常的类型（例如，NameError）参数标准异常中任一种，args 是自已提供的异常参数。

最后一个参数是可选的（在实践中很少使用），如果存在，是跟踪异常对象。
```
##### 参考阅读：[Python 异常处理](https://www.runoob.com/python/python-exceptions.html)

### 72、什么是面向对象的mro?
```
上面58，59题有提及，请查看。
```

### 73、isinstance作用以及应用场景？
```
描述:
isinstance() 函数来判断一个对象是否是一个已知的类型，类似 type()。

    isinstance() 与 type() 区别：

        type() 不会认为子类是一种父类类型，不考虑继承关系。

        isinstance() 会认为子类是一种父类类型，考虑继承关系。

    如果要判断两个类型是否相同推荐使用 isinstance()。

语法:

以下是 isinstance() 方法的语法:

isinstance(object, classinfo)

参数:

    object -- 实例对象。
    classinfo -- 可以是直接或间接类名、基本类型或者由它们组成的元组。

返回值

如果对象的类型与参数二的类型（classinfo）相同则返回 True，否则返回 False。。
```
##### 参考阅读：[Python isinstance()函数](http://www.runoob.com/python/python-func-isinstance.html)
 
### 74、写代码并实现： 
```
 Given an array of integers, return indices of the two numbers such that 
 they add up to a specific target.You may assume that each input would 

 have exactly one solution, and you may not use the same element twice.

 Example:

     Given nums = [2, 7, 11, 15], target = 9,
    
     Because nums[0] + nums[1] = 2 + 7 = 9,
    
                return [0, 1]

				
class Solution():
	
	
	def twoSum(self, nums, targets):
		"""
		:type nums: List[int]
        :type target: int
        :rtype: List[int]
		"""
		dct = {}
		
		for index, value in enumerate(nums):
			j = target - value
			if j in dct:
				return [ dct[j], index]
			else:
				dct[value] = index
 ```

### 75、json序列化时，可以处理的数据类型有哪些？如何定制支持datetime类型？
```
JSON类型            Python类型
{}                  dict
[]                  list
"string"            str
1234.56             int或float
true                True
false               False
null                None

自定义时间序列化转换器
import json
from json import JSONEncoder
from datetime import datetime
class ComplexEncoder(JSONEncoder):
    def default(self, obj):
        if isinstance(obj, datetime):
            return obj.strftime('%Y-%m-%d %H:%M:%S')
        else:
            return super(ComplexEncoder,self).default(obj)
d = { 'name':'alex','data':datetime.now()}
print(json.dumps(d,cls=ComplexEncoder))
# {"name": "alex", "data": "2018-05-18 19:52:05"}
```

### 76、json序列化时，默认遇到中文会转换成unicode，如果想要保留中文怎么办？
```
import json
a=json.dumps({"ddf":"你好"},ensure_ascii=False)
print(a) #{"ddf": "你好"}
```

### 77、什么是断言？应用场景？
```
请参考下面的阅读。
```
##### 参考阅读： [Python 中何时使用断言？](http://blog.jobbole.com/76285/)

### 78、有用过with statement吗？它的好处是什么？
```
Python中的有关上下文管理器的部分。
```
##### 参考阅读：[with statement - CSDN博客](https://blog.csdn.net/xtydtc/article/details/52037489)

### 79、使用代码实现查看列举目录下的所有文件。
```
提供4个方法理出文件夹内的所有内容

Python
#方法1：使用os.listdir
import os
for filename in os.listdir(r'c:\windows'):
    print filename
 
#方法2：使用glob模块，可以设置文件过滤
import glob
for filename in glob.glob(r'c:\windows\*.exe'):
    print filename
 
#方法3：通过os.path.walk递归遍历，可以访问子文件夹
import os.path
def processDirectory ( args, dirname, filenames ):
    print 'Directory',dirname
    for filename in filenames:
        print ' File',filename
 
os.path.walk(r'c:\windows', processDirectory, None )
 
#方法4：非递归
import os
for dirpath, dirnames, filenames in os.walk('c:\\winnt'):
    print 'Directory', dirpath
    for filename in filenames:
        print ' File', filename
#该代码片段来自于: http://www.sharejs.com/codes/python/211
```

### 80、简述 yield和yield from关键字。
```
请参考下面的文章。
```
##### 参考阅读：[python3中的yield from语句](https://blog.csdn.net/wangjianno2/article/details/51935977)


----
# 第二部分 网络编程和并发（34题）


### 1、简述 OSI 七层协议。
```
应用层:
与其它计算机进行通讯的一个应用，它是对应应用程序的通信服务的。
例如，一个没有通信功能的字处理程序就不能执行通信的代码，
从事字处理工作的程序员也不关心OSI的第7层。
但是，如果添加了一个传输文件的选项，
那么字处理器的程序员就需要实现OSI的第7层。
示例：TELNET，HTTP，FTP，NFS，SMTP等。

表示层:
这一层的主要功能是定义数据格式及加密。
例如，FTP允许你选择以二进制或ASCII格式传输。
如果选择二进制，那么发送方和接收方不改变文件的内容。
如果选择ASCII格式，发送方将把文本从发送方的字符集转换成标准的ASCII后发送数据。
在接收方将标准的ASCII转换成接收方计算机的字符集。示例：加密，ASCII等。

会话层:
它定义了如何开始、控制和结束一个会话，
包括对多个双向消息的控制和管理，
以便在只完成连续消息的一部分时可以通知应用，
从而使表示层看到的数据是连续的，在某些情况下，
如果表示层收到了所有的数据，则用数据代表表示层。示例：RPC，SQL等。

传输层:
这层的功能包括是否选择差错恢复协议还是无差错恢复协议，
及在同一主机上对不同应用的数据流的输入进行复用，
还包括对收到的顺序不对的数据包的重新排序功能。示例：TCP，UDP，SPX。

网络层:
这层对端到端的包传输进行定义，它定义了能够标识所有结点的逻辑地址，
还定义了路由实现的方式和学习的方式。
为了适应最大传输单元长度小于包长度的传输介质，
网络层还定义了如何将一个包分解成更小的包的分段方法。
示例：IP，IPX等。

数据链路层:
它定义了在单个链路上如何传输数据。
这些协议与被讨论的各种介质有关。示例：ATM，FDDI等。

物理层:
OSI的物理层规范是有关传输介质的特这些规范通常也参考了其他组织制定的标准。
连接头、帧、帧的使用、电流、编码及光调制等都属于各种物理层规范中的内容。
物理层常用多个规范完成对所有细节的定义。示例：Rj45，802.3等。

自己说：理解这OSI七层模型后，我们就能明白网络的工作原理，
比如一条微信是怎样发送给对方，对方又是怎么收到的。
事实上此模型并没有大规模采用，我们常用的是TCP/IP四层模型，请参考下面的阅读。
```
#### 参考阅读：[网络七层协议](https://baike.baidu.com/item/%E7%BD%91%E7%BB%9C%E4%B8%83%E5%B1%82%E5%8D%8F%E8%AE%AE/6056879)
[TCP/IP四层模型简述](https://blog.csdn.net/a3125504x/article/details/63684572)

### 2、什么是C/S和B/S架构？
```
C/S(Client/Server）结构，即客户机和服务器结构。它是软件系统体系结构，
通过它可以充分利用两端硬件环境的优势，
将任务合理分配到Client端和Server端来实现，降低了系统的通讯开销。
C/S结构可以看做是胖客户端架构。客户端实现绝大多数的业务逻辑处理和界面展示，
作为客户端的部分需要承受很大的压力，从分利用客户端的资源，对客户机的要求较高。

B/S(Browser/Server）结构即浏览器和服务器结构。它是随着Internet技术的兴起，
对C/S结构的一种变化或者改进的结构。在这种结构下，用户工作界面是通过WWW浏览器来实现，
极少部分事务逻辑在前端（Browser）实现，但是主要事务逻辑在服务器端（Server）实现，
形成所谓三层3-tier结构。这样就大大简化了客户端电脑载荷，
减轻了系统维护与升级的成本和工作量，降低了用户的总体成本（TCO）。
B/S结构可以看作是瘦客户端，只是把显示的较少的逻辑交给了Web浏览器，
事务逻辑数据处理在放在了Server端，这样就避免了庞大的胖客户端，减少了客户端的压力。
B/S结构的系统无须特别安装，只有Web浏览器即可。
当然AJAX\Flex等等的普遍使用也有富客户端的发展方向。
```
##### 参考阅读：[C/S和B/S结构概念](https://blog.csdn.net/sinat_35111396/article/details/51535784)

### 3、简述 三次握手、四次挥手的流程。
```
三次握手:

第一次握手：客户端的应用进程主动打开，并向客户端发出请求报文段。其首部中：SYN=1,seq=x。

第二次握手：服务器应用进程被动打开。若同意客户端的请求，则发回确认报文，其首部中：SYN=1,ACK=1,ack=x+1,seq=y。

第三次握手：客户端收到确认报文之后，通知上层应用进程连接已建立，并向服务器发出确认报文，
其首部：ACK=1,ack=y+1。当服务器收到客户端的确认报文之后，也通知其上层应用进程连接已建立。

在这个过程中，通信双方的状态如下图，其中CLOSED：关闭状态、LISTEN：收听状态、SYN-SENT：同步已发送、SYN-RCVD：同步收到、ESTAB-LISHED：连接已建立
```
![](http://img.blog.csdn.net/20161203203726485?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

```
四次挥手:
第一次挥手：数据传输结束以后，客户端的应用进程发出连接释放报文段，
并停止发送数据，其首部：FIN=1,seq=u。

第二次挥手：服务器端收到连接释放报文段之后，发出确认报文，其首部：ack=u+1,seq=v。
此时本次连接就进入了半关闭状态，客户端不再向服务器发送数据。而服务器端仍会继续发送。

第三次挥手：若服务器已经没有要向客户端发送的数据，其应用进程就通知服务器释放TCP连接。
这个阶段服务器所发出的最后一个报文的首部应为：FIN=1,ACK=1,seq=w,ack=u+1。

第四次挥手：客户端收到连接释放报文段之后，必须发出确认：ACK=1,seq=u+1,ack=w+1。
 再经过2MSL(最长报文端寿命)后，本次TCP连接真正结束，通信双方完成了他们的告别。

在这个过程中，通信双方的状态如下图，其中：ESTAB-LISHED：连接建立状态、
FIN-WAIT-1：终止等待1状态、FIN-WAIT-2：终止等待2状态、CLOSE-WAIT：关闭等待状态、
LAST-ACK：最后确认状态、TIME-WAIT：时间等待状态、CLOSED：关闭状态
```
![](http://img.blog.csdn.net/20161203205925133?watermark/2/text/aHR0cDovL2Jsb2cuY3Nkbi5uZXQv/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70/gravity/Center)

##### 参考阅读：[简述TCP连接的建立与释放（三次握手、四次挥手）](https://www.cnblogs.com/zhuwq585/p/6138775.html)

### 4、什么是arp协议？
```
 在数据链路层的以太网的协议中，每一个数据包都有一个MAC地址。
 我们知道每一块以太网卡都有一个MAC地址，这个地址是唯一的，
 那么IP包是如何知道这个MAC地址的？这就是ARP协议的工作。

ARP（地址解析）协议是一种解析协议，本来主机是完全不知道这个IP对应的是哪个主机的哪个接口，
当主机要发送一个IP包的时候，会首先查一下自己的ARP高速缓存表（最近数据传递更新的IP-MAC地址对应表），
如果查询的IP－MAC值对不存在，那么主机就向网络广播一个ARP请求包，
这个包里面就有待查询的IP地址，而直接收到这份广播的包的所有主机都会查询自己的IP地址，
如果收到广播包的某一个主机发现自己符合条件，那么就回应一个ARP应答包（将自己对应的IP-MAC对应地址发回主机），
源主机拿到ARP应答包后会更新自己的ARP缓存表。源主机根据新的ARP缓存表准备好数据链路层的的数据包发送工作。
```
##### 参考阅读：[ARP（地址解析协议）](https://baike.baidu.com/item/ARP/609343?fr=aladdin)

### 5、TCP和UDP的区别？
```
TCP与UDP区别总结：
1、TCP面向连接（如打电话要先拨号建立连接）;UDP是无连接的，即发送数据之前不需要建立连接
2、TCP提供可靠的服务。也就是说，通过TCP连接传送的数据，无差错，不丢失，不重复，且按序到达;
UDP尽最大努力交付，即不保证可靠交付
3、TCP面向字节流，实际上是TCP把数据看成一连串无结构的字节流;UDP是面向报文的
  UDP没有拥塞控制，因此网络出现拥塞不会使源主机的发送速率降低（对实时应用很有用，如IP电话，实时视频会议等）
4、每一条TCP连接只能是点到点的;UDP支持一对一，一对多，多对一和多对多的交互通信
5、TCP首部开销20字节;UDP的首部开销小，只有8个字节
6、TCP的逻辑通信信道是全双工的可靠信道，UDP则是不可靠信道
```

### 6、什么是局域网和广域网？
```
一、局域网 
局域网（Local Area Network），简称LAN，是指在某一区域内由多台计算机互联成的计算机组。
“某一区域”指的是同一办公室、同一建筑物、同一公司和同一学校等，一般是方圆几千米以内。
局域网可以实现文件管理、应用软件共享、打印机共享、扫描仪共享、工作组内的日程安排、
电子邮件和传真通信服务等功能。局域网是封闭型的，可以由办公室内的两台计算机组成，
也可以由一个公司内的上千台计算机组成。 

二、广域网 
广域网（Wide Area Network），简称WAN，是一种跨越大的、地域性的计算机网络的集合。
通常跨越省、市，甚至一个国家。广域网包括大大小小不同的子网，子网可以是局域网，也可以是小型的广域网。 

三、局域网和广域网的区别 
局域网是在某一区域内的，而广域网要跨越较大的地域，那么如何来界定这个区域呢？
例如，一家大型公司的总公司位于北京，而分公司遍布全国各地，
如果该公司将所有的分公司都通过网络联接在一起，
那么一个分公司就是一个局域网，而整个总公司网络就是一个广域网。
```

### 7、为何基于tcp协议的通信比基于udp协议的通信更可靠？
```
TCP提供可靠的服务。也就是说，通过TCP连接传送的数据，无差错，不丢失，不重复，且按序到达;
UDP尽最大努力交付，即不保证可靠交付
```

### 8、什么是socket？简述基于tcp协议的套接字通信流程?
```

TCP用主机的IP地址加上主机上的端口号作为TCP连接的端点，这种端点就叫做套接字（socket）或插口。
套接字用（IP地址：端口号）表示。
它是网络通信过程中端点的抽象表示，包含进行网络通信必需的五种信息：
连接使用的协议，本地主机的IP地址，本地进程的协议端口，远地主机的IP地址，远地进程的协议端口。

套接字通信流程:
 服务端先初始化Socket实例化一个类拿到对象（才能调用下面的接口），
 然后绑定IP端口(bind)，监听(listen)就是说客户端可以来连我了，调用accept接收链接；
 这时客户端初始化一个socket，然后connect与服务端建立好双向链接与accept对应。
 客户端发送请求数据，服务端处理请求并给客户端回应数据，
 这样一个通信循环；最后关闭套接字，一次交互结束。
```

### 9、什么是粘包？ socket 中造成粘包的原因是什么？ 哪些情况会发生粘包现象？
```
 如客户端只recv(1024), 可结果比1024长那怎么办，
 只好在服务器端的IO缓冲区里把客户端还没收走的暂时存下来，
 等客户端下次再来收，
 所以当客户端第2次调用recv(1024)就会首先把上次没收完的数据先收下来，
 再收df命令的结果。

这个现象叫做粘包，就是指两次结果粘到一起了。它的发生主要是因为socket缓冲区导致的。

所谓粘包问题原因：
（1）主要还是因为接收方不知道消息之间的界限，不知道一次性提取多少字节的数据所造成的。
（2）发送方引起的粘包是由TCP协议本身造成的，TCP为提高传输效率，
	发送方往往要收集到足够多的数据后才发送一个TCP段。
	若连续几次需要send的数据都很少，
	通常TCP会根据优化算法把这些数据合成一个TCP段后一次发送出去，
	这样接收方就收到了粘包数据。

发生粘包的情况：（1）发送端需要等缓冲区满才发送出去，
造成粘包（发送数据时间间隔很短，数据了很小，会合到一起，产生粘包）
（2）接收方不及时接收缓冲区的包，造成多个包接收
（客户端发送了一段数据，服务端只收了一小部分，服务端下次再收的时候还是从缓冲区拿上次遗留的数据，产生粘包）
```

### 10、IO多路复用的作用？
```
这个自己没看明白，请参考下面的文章。
```
##### 参考阅读： [IO多路复用总结](https://blog.csdn.net/godleading/article/details/45042885)

### 11、什么是防火墙以及作用？
```
它可通过监测、限制、更改跨越防火墙的数据流，
尽可能地对外部屏蔽网络内部的信息、结构和运行状况，
 以此来实现网络的安全保护。
在逻辑上，防火墙是一个分离器，一个限制器，
也是一个分析器，有效地监控了内部网和Internet之间的任何活动，
 保证了内部网络的安全。
```

### 12、select、poll、epoll 模型的区别？
```
在第10中有详细介绍。
```

### 13、简述 进程、线程、协程的区别 以及应用场景？
```
1.线程和进程： 
线程是属于进程的，线程运行在进程空间内，同一进程所产生的线程共享同一内存空间，
当进程退出时该进程所产生的线程都会被强制退出并清除。
线程可与属于同一进程的其它线程共享进程所拥有的全部资源，
但是其本身基本上不拥有系统资源，
只拥有一点在运行中必不可少的信息(如程序计数器、一组寄存器和栈)。

2.线程、进程与协程：
线程和进程的操作是由程序触发系统接口，
最后的执行者是系统；协程的操作则是程序员
协程存在的意义：对于多线程应用，CPU通过切片的方式来切换线程间的执行，
线程切换时需要耗时（保持状态，下次继续）。
协程，则只使用一个线程，在一个线程中规定某个代码块执行顺序。
协程的适用场景： 当程序中存在大量不需要CPU的操作时（IO），适用于协程；
```
##### 参考阅读：[进程、线程、协程之概念理解](https://www.cnblogs.com/work115/p/5620272.html)

### 14、GIL锁是什么鬼？
```
线程全局锁(Global Interpreter Lock),即Python为了保证线程安全而采取的独立线程运行的限制,
说白了就是一个核只能在同一时间运行一个线程.对于io密集型任务，
python的多线程起到作用，但对于cpu密集型任务，
python的多线程几乎占不到任何优势，还有可能因为争夺资源而变慢。
```
##### 参考阅读：[Python的GIL是什么鬼，多线程性能究竟如何](http://cenalulu.github.io/python/gil-in-python/)

### 15、Python中如何使用线程池和进程池？
```
请参考下面的文章。
```
##### 参考阅读：[Python并发编程之线程池/进程池](http://python.jobbole.com/87272/)

### 16、threading.local的作用？
```
threading.local的目的是为了解决线程间对数据的访问问题，有点类似于全局变量与局部变量。请参考下面的文章。
```
##### 参考阅读：[深入理解Python中的ThreadLocal变量](http://python.jobbole.com/86150/)

### 17、进程之间如何进行通信？
```
Python: 进程间通讯有多种方式，包括信号，管道，消息队列，信号量，共享内存，socket等
```
##### 参考阅读：[Python的进程间通信](https://www.cnblogs.com/Xjng/p/3873371.html)

### 18、什么是并发和并行？
```
1、并行就是两个任务同时运行，就是甲任务进行的同时，乙任务也在进行。

2、并发是指两个任务都请求运行，而处理器只能按受一个任务，
就把这两个任务安排轮流进行，由于时间间隔较短，使人感觉两个任务都在运行。
```

### 19、进程锁和线程锁的作用？
```
　　线程锁:大家都不陌生，主要用来给方法、代码块加锁。当某个方法或者代码块使用锁时，
那么在同一时刻至多仅有有一个线程在执行该段代码。当有多个线程访问同一对象的加锁方法/代码块时，
同一时间只有一个线程在执行，其余线程必须要等待当前线程执行完之后才能执行该代码段。
但是，其余线程是可以访问该对象中的非加锁代码块的。

　　进程锁:也是为了控制同一操作系统中多个进程访问一个共享资源，只是因为程序的独立性，
各个进程是无法控制其他进程对资源的访问的，但是可以使用本地系统的信号量控制。
```

### 20、解释什么是异步非阻塞？
```
同步、异步：

    概念：消息的通知机制
    解释：涉及到IO通知机制；所谓同步，就是发起调用后，被调用者处理消息，
	必须等处理完才直接返回结果，没处理完之前是不返回的，调用者主动等待结果；
	所谓异步，就是发起调用后，被调用者直接返回，但是并没有返回结果，
	等处理完消息后，通过状态、通知或者回调函数来通知调用者，调用者被动接收结果。

阻塞、非阻塞：

    概念：程序等待调用结果时的状态
    解释：涉及到CPU线程调度；所谓阻塞，就是调用结果返回之前，
	该执行线程会被挂起，不释放CPU执行权，线程不能做其它事情，
	只能等待，只有等到调用结果返回了，才能接着往下执行；
	所谓非阻塞，就是在没有获取调用结果时，不是一直等待，线程可以往下执行，
	如果是同步的，通过轮询的方式检查有没有调用结果返回，
	如果是异步的，会通知回调。
```

### 21、路由器和交换机的区别？
```
交换机:
1. 用于同一网络内部数据的快速传输
2. 转发决策通过查看二层头部完成
3. 转发不需要修改数据帧
4. 工作在 TCP/IP 协议的二层 —— 数据链路层工作简单，
5. 直接使用硬件处理

路由器:
1. 用于不同网络间数据的跨网络传输
2. 转发决策通过查看三层头部完成
3. 转发需要修改 TTL ，IP 头部校验和需要重新计算，数据帧需要重新封装
4. 工作在 TCP/IP 协议的三层 —— 网络层
5. 工作复杂，使用软件处理
```

### 22、什么是域名解析？
```
域名解析是把域名指向网站空间IP，让人们通过注册的域名可以方便地访问到网站的一种服务。
IP地址是网络上标识站点的数字地址，为了方便记忆，采用域名来代替IP地址标识站点地址。
域名解析就是域名到IP地址的转换过程。域名的解析工作由DNS服务器完成。
```

### 23、如何修改本地hosts文件？
```
Linux: /etc/hosts

Windows: C:\Windows\System32\drivers\etc
```

### 24、生产者消费者模型应用场景及优势？
```
某些模块负责生产数据，这些数据由其他模块来负责处理。
产生数据的模块称为生产者，而处理数据的模块称为消费者。
在生产者与消费者之间的缓冲区称之为仓库。生产者负责往仓库运输商品，
而消费者负责从仓库里取出商品，这就构成了生产者消费者模式。
```
##### 参考阅读：[用Python多线程实现生产者消费者模式](http://python.jobbole.com/87592/)

### 25、什么是cdn？
```
CDN的全称是Content Delivery Network，即内容分发网络。
其基本思路是尽可能避开互联网上有可能影响数据传输速度和稳定性的瓶颈和环节，
使内容传输的更快、更稳定。通过在网络各处放置节点服务器所构成的在现有的互联网基础之上的一层智能虚拟网络，
CDN系统能够实时地根据网络流量和各节点的连接、负载状况以及到用户的距离和响应时间等综合信息
将用户的请求重新导向离用户最近的服务节点上。其目的是使用户可就近取得所需内容，
解决 Internet网络拥挤的状况，提高用户访问网站的响应速度。
```

### 26、LVS是什么及作用？
```
 一.LVS是什么？

LVS的英文全称是Linux Virtual Server，即Linux虚拟服务器。它是我们国家的章文嵩博士的一个开源项目。
在linux内存2.6中，它已经成为内核的一部分，在此之前的内核版本则需要重新编译内核。
二.LVS能干什么？

LVS主要用于多服务器的负载均衡。它工作在网络层，可以实现高性能，高可用的服务器集群技术。
它廉价，可把许多低性能的服务器组合在一起形成一个超级服务器。
它易用，配置非常简单，且有多种负载均衡的方法。
它稳定可靠，即使在集群的服务器中某台服务器无法正常工作，也不影响整体效果。
另外可扩展性也非常好。
```
##### 参考阅读：[LVS 工作模式以及工作原理](https://blog.csdn.net/caoshuming_500/article/details/8291940)
[Linux服务器集群系统（一）](http://www.linuxvirtualserver.org/zh/lvs1.html#2)

### 27、Nginx是什么及作用？
```
Nginx是一款轻量级的Web 服务器/反向代理服务器及电子邮件（IMAP/POP3）代理服务器，
并在一个BSD-like 协议下发行。其特点是占有内存少，并发能力强，
事实上nginx的并发能力确实在同类型的网页服务器中表现较好，
中国大陆使用nginx网站用户有：百度、京东、新浪、网易、腾讯、淘宝等。
```

### 28、keepalived是什么及作用?
```
 Keepalived是Linux下一个轻量级别的高可用解决方案。高可用(High Avalilability,HA)，
 其实两种不同的含义：广义来讲，是指整个系统的高可用行，狭义的来讲就是之主机的冗余和接管，
 
 作用:
	Keepalived的作用是检测服务器的状态，如果有一台web服务器宕机，或工作出现故障，
	Keepalived将检测到，并将有故障的服务器从系统中剔除，同时使用其他服务器代替该服务器的工作，
	当服务器工作正常后Keepalived自动将服务器加入到服务器群中，
	这些工作全部自动完成，不需要人工干涉，需要人工做的只是修复故障的服务器。
```

### 29、haproxy是什么以及作用？
```
HAProxy是一个使用C语言编写的自由及开放源代码软件[1]，
其提供高可用性、负载均衡，以及基于TCP和HTTP的应用程序代理。
HAProxy特别适用于那些负载特大的web站点，这些站点通常又需要会话保持或七层处理。
HAProxy运行在当前的硬件上，完全可以支持数以万计的并发连接。
并且它的运行模式使得它可以很简单安全的整合进您当前的架构中，
同时可以保护你的web服务器不被暴露到网络上。
```

### 30、什么是负载均衡？
```

负载均衡 建立在现有网络结构之上，
它提供了一种廉价有效透明的方法扩展网络设备和服务器的带宽、
增加吞吐量、加强网络数据处理能力、提高网络的灵活性和可用性

负载均衡，英文名称为Load Balance，其意思就是分摊到多个操作单元上进行执行，
例如Web服务器、FTP服务器、企业关键应用服务器和其它关键任务服务器等，从而共同完成工作任务。
```

### 31、什么是rpc及应用场景？
```
RPC（Remote Procedure Call）—远程过程调用，它是一种通过网络从远程计算机程序上请求服务，
而不需要了解底层网络技术的协议。RPC协议假定某些传输协议的存在，如TCP或UDP，
为通信程序之间携带信息数据。在OSI网络通信模型中，RPC跨越了传输层和应用层。
RPC使得开发包括网络分布式多程序在内的应用程序更加容易。

RPC采用客户机/服务器模式。请求程序就是一个客户机，而服务提供程序就是一个服务器。
首先，客户机调用进程发送一个有进程参数的调用信息到服务进程，然后等待应答信息。
在服务器端，进程保持睡眠状态直到调用信息到达为止。
当一个调用信息到达，服务器获得进程参数，计算结果，发送答复信息，
然后等待下一个调用信息，最后，客户端调用进程接收答复信息，
获得进程结果，然后调用执行继续进行。

RPC是只远程过程调用，也就是说两台服务器A,B, 一个应用部署在A服务器上，
另一个应用部署在B服务器上，A服务器上的应用想要调用B服务器上的应用提供的方法/函数，
由于不在一个内存空间，不能直接调用，需要通过网络来表达调用的语意和传递调用的参数。
```

### 32、简述 asynio模块的作用和应用场景?
```
这个不太懂，请参考下面的文章。
```
##### 参考阅读：[python中重要的模块--asyncio](https://www.cnblogs.com/zhaof/p/8490045.html)
[Python并发编程之协程/异步IO](http://python.jobbole.com/87202/)

### 33、简述gevent模块的作用和应用场景?
```
gevent是基于协程的Python网络库。特点：

    基于libev的快速事件循环(Linux上epoll，FreeBSD上kqueue）。

    基于greenlet的轻量级执行单元。

    API的概念和Python标准库一致(如事件，队列)。

    可以配合socket，ssl模块使用。

    能够使用标准库和第三方模块创建标准的阻塞套接字(gevent.monkey)。

    默认通过线程池进行DNS查询,也可通过c-are(通过GEVENT_RESOLVER=ares环境变量开启）。

    TCP/UDP/HTTP服务器

    子进程支持（通过gevent.subprocess）

    线程池
```
##### 参考阅读：[gevent - 廖雪峰的官方网站](https://www.liaoxuefeng.com/wiki/001374738125095c955c1e6d8bb493182103fac9270762a000/001407503089986d175822da68d4d6685fbe849a0e0ca35000)

### 34、twisted框架的使用和应用？
```
请参考下面的文章。
```
##### [Python Twisted介绍](https://www.cnblogs.com/xianguang/p/7027661.html)


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