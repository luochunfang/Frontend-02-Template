### 关于产生式
##### 语法结构名： 尖括号括起来的名称
##### 终结符： 简单结构（基础结构）， 引号和中间的字符表示终结符
##### 非终结符: 复杂结构
##### 可以有括号、*表示重复多次、| 表示或、 +表示至少一次

### 语言分类
##### 1、从用途 
######（1）数据描述语言，如：HTML、XAML、SQL、CSS等
###### （2）编程语言： java、c、c++、c#、ruby、perl
lisp、clojure、haskell、javascript等

##### 2、表达方式
###### （1）声明式： JSON、HTML、XAML、SQL、CSS、：LISP、Clojure、Haskell、MATLAB、R
###### （2）命令式：  C、C++、JAVA、C#、Python、Ruby、Perl、javacript、go、php、.net

### 一般命令式语言包括：
##### atom(原子)、expression(表达式)、statement(语句)、structure(结构化)、Program(组织代码)

### js类型之Number(IEEE 754 标准 双精度浮点型)
##### 在计算机内存中的表示为： sign(1 符号位) + exponent( 11 精度位)  + fraction（52 有效数字）， 其中fraction有一隐藏位为1
##### TODO 看了相关博客，对IEEE 754 标准了解依然模糊，具体是怎么完整的形成的一个数字需继续研究。

### js类型之string
##### 常用字符集为： ASCII（127字符）、Unicode、UCS、GB（GB2312、GBK、GB18030）、ISO-8859（地区性）、BIG5
##### 常用编码方式： UTF-8、UTF-16（TextEncoder 方法可指定string的编码方式）
##### TODO 关于编码方式在计算机内存的方式需深入研究

### js之Object
##### 思想：（1）归类：多继承 （2）分类：单继承
##### 在设计对象的状态和行为时，我们不应该受到语言描述的干扰，总是遵循“行为改变状态”的原则
##### 对象包括data property(数据属性：[[value]]、writable、enumerable、configurable)和Accessor property（访问器属性: get、set、enumerable、configurable）
##### 访问器属性多数用来描述行为，有时同时用来描述状态行为；数据属性存储函数时也可用来描述行为
##### 原型链： 循着原型层层往上直至顶端，即原型链
##### TODO：作业里说的JS对象的特殊行为？？？啥意思，没太明白？
