为期6天的python速成营结束了，学完后才觉时间太短，知识的海洋是无穷的，三人行必有我师，6天的内容将我从一个i小白变成了一个对python学习颇有兴趣的人，同学们的学习氛围非常浓厚，老师尽心尽责，给我们寄予了非常多的编程上的启蒙。

正值2020春节前几天，在这次的python速成营，我学习到python基础语法，数据类型，函数，字符串，列表，元组，字典，面向对象，继承与多态，文件操作，线等以及python基础类库，基本涵盖了python的全面基础知识。自己也一直在坚持打卡，每天7：30准时在直播间聆听老师授课，不放过每一个不懂的地方，请教老师或者同学，收获满满，能够通过自己动手将每天的课后作业保质保量完成，给自己点赞，也给速成营的每一个老师，同学点赞，我们一起在知识的海洋里遨游，以此也让我们的2020春节收获满满。

千言万语，还是想给大家分享一些我在python学习中总结的一些干货，供大家参考。因为自己也是小白，所以总结的也比较小白，适合跟我一样的小白同学参考。

## 预习：

*Notebook使用中的一些快捷键*：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210104923427.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

## 第一天：

1.命令行中运行Python代码：python 文件路径

2.Notebook中运行python代码：! Python 文件路径

3.Python中的字符串类型无法直接转换成int类型，需要将字符串类型先转成float，再转成int类型。例如：print(int(float("12.0")))。

4.python中的关键字和标识符命名：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105200134.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

一. **列表**：List可以进行修改，如使用append或者pop等进行修改，使用的是中括号。

二. **元组**：tuple不可以进行修改，使用的是小括号。

三. **字典**：dict可以进行修改，使用的是大括号，但是修改或者查询其中的值时使用的是中括号。

四. **集合**：set与dict相类似，也是一组key的集合，使用的是大括号，但是不存储value，key的值不可以重复。

五．**区分**：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105304540.png#pic_center)

六：**条件判断和循环语句**：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105349355.png#pic_center)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105349349.png#pic_center)

## 第二天：

1.字符串和List的切片使用：比如：name[1:3]只是包前不包后。从1开始取，到3就结束，但不包括3。

默认是正向切片，-1指的是负向切片。

2.字符串查找：有find和index两种

***List.append和list.extend的区别在于，append是整体的添加，extend是非整体的添加。***

***重点：格式输出***

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105647446.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



例如：把7先给d，然后%%表示输出一个%。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105710333.png#pic_center)

***列表生成式： 就是把一个循环压缩在一起。***



**生成器**：

**作用：通过列表生成式，我们可以直接创建一个列表。但是，受到内存限制，列表容量肯定是有限的。而且，创建一个包含100万个元素的列表，不仅占用很大的存储空间，如果我们仅仅需要访问前面几个元素，那后面绝大多数元素占用的空间都白白浪费了。**

有以下两种形式：

1. 类似列表生成式子

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105838599.png#pic_center)

2. 基于函数

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105846166.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



## 第三天：

**函数的参数传递**：这里一共讲了5种。

1.**位置参数**：

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021021010592856.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

2.**缺省参数**：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210105947567.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**3.可变参数**：

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021021011003778.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**4.关键则参数：**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110043716.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**5.命名关键字参数：**

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021021011005117.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

***参数还可以组合使用：

关键字参数和命名关键字参数如果混合使用，命名关键字前面无须加*。***

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110100779.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**匿名表达式：**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110118802.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

***高阶函数：函数的函数***

**Python中的常见的内置的高阶函数：**map/reduce/sorted

**Map函数：**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110203591.png#pic_center)

**Reduce函数：**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110210269.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**Sorted函数：**

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021021011022172.png#pic_center)

**装饰器**：

装饰器一般用在日志中，通过平面的方式使得代码更加的clean。

装饰器一般有四种情况：

1. 函数名可以作为函数的变量

2. 函数中可以定义函数

3. 函数是可以作为参数传递的

4. 函数是可以作为函数返回值的

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110252883.png#pic_center)

## 第四天：

**类**：

**__init__是一个构造初始化函数。Self指的是类本身，类函数的第一个参数要求是self，可以写也可以不写，但类中的函数或者方法最好写。**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110444370.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110512666.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110333654.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**类属性：所有对象共享的数据**

**类方法：所有对象共享的方法**

***私有属性和私有方法：私有成员不可有直接进行访问，要想访问需要在访问前面加上 _类名，例如此例中就是要在访问的成员前面加上_Athlete。**

## 第五天：

**继承**:

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021021011052485.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**多态**：即父类被多个子类继承

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110543323.png#pic_center)

**多继承**：即子类继承多个父类

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110826962.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**模块**：

import sys

导入sys模块 sys.path.append('work')

将模块athlete.py添加到模块搜索路径

from athlete import *

导入athlete模块，使用athlete模块下的所有代码

注意：

import sys

sys.path.append('mywork')//mywork是输入你的工作路径

from athlete import * //*就是输入你所要重用的代码模块文件路径

## 第六天：

**创建并写入文件**：

with open('work/loren.txt','w+') as f:

for i in range(5000000):

f.write('loren,2011-11-3,270,3.59,4.11,3:11,3:23,4-10,3-23,4:10,4.21,4-21')

f.write('\n')

```

**文件处理**：文件内容中有异常行，但是后面内容还需继续输出，有下面的两种方法：

**1.try except**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110944784.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

**2.代码判断**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210110952379.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

3.更加**clean**的写法，使用with打开和关闭文件，就不用写close了

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210111015384.png#pic_center)

**File对象的函数列表**：

1．**seek()** 函数用于将文件指针移动至指定位置# 将文件指针从文件开头，向后移动到 5 个字符的位置：f.seek(5)

2．当使用 **read()** 函数从文件中读取 3 个字符之后，文件指针同时向后移动了 3 个字符的位置。这就表明，当程序使用文件对象读写数据时，文件指针会自动向后移动：读写了多少个数据，文件指针就自动向后移动多少个位置。

**3. print(f.read(3)) -----读取前3个字符串

print(f.tell()) -------指针向后移动3个位置**

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210111115353.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



**对象转JSON:**

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021021011114199.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)

返回当前路径下文件和文件夹名：使用print(listdir)

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210111206777.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



***如果dir1中又包含文件夹该怎么办呢？***

*答：需要遍历文件目录进行查找所有的txt格式的文件*

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210111227860.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



**进程和线程**：

只使用进程的方式：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210111249586.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



**使用进程+线程的方式**：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210111300733.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)



**进程和线程的区别**：

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210210111309293.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3dlaXhpbl80NjE3NzM2Ng==,size_16,color_FFFFFF,t_70#pic_center)
