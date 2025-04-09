# 初识python

> 2024年7月8日 18:10

![](.\image\PYTHON\image1.jpeg)

> 分区 安装与环境配置 的第 1 页
>
> python环境的安装
>
> 2024年7月8日 18:18
>
> 官方网站：python.org
>
> Windows系统安装：打开安装包，自定义安装，勾选"Add python to
> path"，注意安装路径安装是否成功检验，打开Windows的cmd，输入python回车，会显示安装的版本信息
> mac系统安装：打开pkg安装包，输入系统密码
>
> Linux系统安装：
>
> ![](.\image\PYTHON\image2.jpeg) 
>  
>
> 官网中找到下载指令，在终端中执行官网的下载指令，下载压缩包
>
> ![](.\image\PYTHON\image3.jpeg) 
>  
>
> ![](.\image\PYTHON\image4.jpeg) 
>  解压压缩包
>
> ![](.\image\PYTHON\image5.jpeg) 
>  选择安装路径源码编译
>
> ![](.\image\PYTHON\image6.jpeg) 
>  
>
> 为方便使用，可设置软链接
>
> Linux默认安装2.7版本的python，如果安装版本顶替掉了默认版本，则需要去修改一下yum
>
> 的依赖库
>
> 分区 安装与环境配置 的第 2 页

### 第一个python程序

> 2024年7月10日 19:42

![](.\image\PYTHON\image7.jpeg)

> 在cmd中直接敲就行
>
> cmd打开快捷键win+r

#### python解释器

> 2024年7月10日 19:44
>
> 计算机不认识python语言，但是python语言有自己的解释器将python语言翻译为计算机的语言（二进制）

![](.\image\PYTHON\image8.jpeg)

> 安装配置环境的过程，就是在安装解释器，安装目录中的python.exe就是解释器
>
> python代码文件后缀是.py
>
> 可在cmd中直接运行.py文件

# pycharm开发工具安装与使用

> 2024年7月10日 20:33

![](.\image\PYTHON\image9.jpeg)

![](.\image\PYTHON\image10.jpeg)

# 常用快捷键

> 2024年7月20日 14:19

![](.\image\PYTHON\image11.jpeg)

> Ctrl+shift+f10 运行
>
> Ctrl+z 撤回
>
> ctrl+/ 注释选中内容

###### 字面量

> 2024年7月20日 14:37
>
> 字面量含义：代码中被写下的固定值包括六大数据类型
>
> ![](.\image\PYTHON\image12.jpeg) 
>  

![](.\image\PYTHON\image13.png)

> 分区 基本概念 的第 7 页

### 特殊字面量none

> 2024年8月2日 14:04

![](.\image\PYTHON\image14.jpeg)

![](.\image\PYTHON\image15.jpeg)![](.\image\PYTHON\image16.jpeg)

> 分区 基本概念 的第 8 页

# 注释

> 2024年7月20日 14:45
>
> **注释**：代码中用于解释的文字，不是代码，在代码运行过程中不会被执行注释分为单行注释和多行注释
>
> **单行注释**：以#开头，#右边写下文字
>
> ![](.\image\PYTHON\image17.jpeg) 
>  
>
> ![](.\image\PYTHON\image18.jpeg) 
>  ![](.\image\PYTHON\image19.png) 
>  **多行注释**：以一对（\"\"\"注释内容\"\"\"）三引号括起来的的内容

# 变量

> 2024年7月20日 14:57
>
> 变量就是在代码运行过程中存储数据用的定义语法
>
> 变量名=变量值
>
> \*注：这里并不需要像c/c++一样，在变量名前定义数据类型，直接写变量名就行

# 数据类型

> 2024年7月20日 15:21

######### 变量无类型，数据有类型 查询数据类型的关键词type type的使用

1. 直接输出结果

> print（type（变量名或固定值））
>
> 将会输出一个字符串，结果为变量名的数据类型

2. 存储查询结果

> 新的变量名=type（变量名或固定值）
>
> 这样的结果就是左边的变量名将会储存一个type类型的数据，内容为查询到的变量类型
>
> type返回的数据类型就是type

######### python中变量是没有数据类型的

- C/C++ 中的变量具有明确的数据类型，且只能固定为该类型。
- Python 中的变量并不需要声明数据类型，类型是根据赋值动态决定的。

> 简单地说，C/C++ 中变量具有静态、强类型特性，而 Python
> 变量则是动态、弱类型的，这使得 Python
> 在灵活性和易用性上有所优势，但同时也可能在类型检查上造成一些潜在的运行时错误。

# 数据类型转换

> 2024年7月20日 15:37
>
> 比如将字符串转换为整型浮点型，将整型转换为字符串常见的转换语句
>
> ![](.\image\PYTHON\image20.jpeg) 
>  
>
> 这三个语句都是有返回值的，可以直接用print去输出，也可以用变量储存返回值
>
> 万物皆可转字符串，但是字符串不一定能转数字
>
> 强行转数字会报错
>
> 数字转数字：整型转浮点无变化，浮点转整型会丢失精度（去掉小数部分，保留整数部分，不是四舍五入）
>
> 标识符
>
> 2024年7月22日 14:25
>
> 标识符：用户在写代码过程中，给变量、方法、类取的名字
>
> python支持的字符：英文、数字、下划线、中文（虽然支持中文，但是并不建议使用中文）
>
> （程序能够区分大小写）数字不能用在开头
>
> 关键字不能用作标识符
>
> ![](.\image\PYTHON\image21.jpeg) 
>  
>
> 分区 基本概念 的第 13 页

# 运算符

> 2024年7月22日 14:43

![](.\image\PYTHON\image22.png)![](.\image\PYTHON\image23.jpeg)

> 分区 基本概念 的第 14 页
>
> 字符串
>
> 2024年7月22日 14:54
>
> 一、字符串的三种定义方式

1. 单引号定义法

> name='杨花落尽子规啼'

2. 双引号定义法

> name="杨花落尽子规啼"

3. 三引号定义法

> name=\"\'杨花落尽子规啼\'\"
>
> 三引号如果用变量接收，那就是字符串，如果没有变量接受，那就是注释

4. 引号嵌套

> ![](.\image\PYTHON\image24.jpeg) 
>  ![](.\image\PYTHON\image25.jpeg) 
>  如果一个字符串中有引号
>
> 二、字符串的拼接
>
> 如果有两个字符串，在字符串间用+号就可以拼接两个字符串
>
> ![](.\image\PYTHON\image26.jpeg) 
>  
>
> +无法实现多个类型的拼接，如整型+字符串就会报错
>
> 三、字符串格式化
>
> 通过占位的方式实现字符串拼接
>
> 格式化方式一
>
> 在字符串内使用占位符号%，%后跟数据类型，如**字符串类型s、整型%d、浮点型%f**
>
> ![](.\image\PYTHON\image27.jpeg) 
>  
>
> **格式化精度控制：**

![](.\image\PYTHON\image28.jpeg)

> 格式化方式二：快速格式化

![](.\image\PYTHON\image29.jpeg)

> 缺点是不能实现精度控制
>
> 四、表达式的格式化
>
> 表达式：一个有结果的代码语句，如11+11，2\*3
>
> 在格式化过程中，如果写的是表达式，那么输出结果将是表达式的运行结果，如%（1\*2）输出不是"1\*2"，而是2

![](.\image\PYTHON\image30.jpeg)

# 数据输入（input）

> 2024年7月22日 17:07

![](.\image\PYTHON\image31.jpeg)

> 代码input中写下的内容将会被输出在屏幕上
>
> ![](.\image\PYTHON\image32.jpeg) 
>  
>
> 无论输入什么数据，input获取的都是字符串类型

## 数据输出（print）

> 2024年7月27日 15:54
>
> print输出不同数据类型变量
>
> print（N1，N2......N）
>
> 将会输出N1+N2+...+N为一行的字符串，逗号隔开将会产生一个空格
>
> print取消换行，若有多条print语句，在不需要换行的句子后加上end=''就可以实现换行操作
>
> ![](.\image\PYTHON\image33.jpeg) 
>  
>
> ![](.\image\PYTHON\image34.png) 
>  ![](.\image\PYTHON\image35.jpeg) 
>  制表符"\\t"

# 布尔类型和运算比较符

> 2024年7月24日 13:02
>
> 布尔类型用于比较真和假布尔数据类型
>
> ture是真 false是假
>
> 布尔类型的变量可以通过定义得到
>
> 格式为：***变量名=ture* 或 *变量名=false***
>
> 布尔类型也可以通过运算比较得到格式为：***变量名=比较式***
>
> 比较运算符用于比较真和假
>
> ![](.\image\PYTHON\image36.jpeg) 
>  
>
> 应该注意的是，单个等号代表赋值运算，两个等号才能表示相等判断

# if语句的基本格式

> 2024年7月24日 16:05

![](.\image\PYTHON\image37.jpeg)![](.\image\PYTHON\image38.jpeg)![](.\image\PYTHON\image39.jpeg)

## if else 组合语句判断

> 2024年7月24日 16:06

![](.\image\PYTHON\image40.jpeg)![](.\image\PYTHON\image41.jpeg)

# if_elif_else组合使用

> 2024年7月24日 16:07

![](.\image\PYTHON\image42.jpeg)

> 多个判断条件下，按顺序判断，如果有了一个条件满足，那么剩下的条件判断将不会被执行

![](.\image\PYTHON\image43.jpeg)

> ![](.\image\PYTHON\image44.jpeg) 
>  

##### 判断语句的嵌套

> 2024年7月24日 16:29
>
> 嵌套判断就是有层次的判断
>
> ![](.\image\PYTHON\image45.jpeg) 
>  
>
> 此外，else的配对需要看缩进，else与缩进一致的if语句配对，如果有多个缩进一致的if语句，那么else与最近的if语句配对
>
> 分区 判断与循环 的第 24 页

# while循环

> 2024年7月26日 16:32
>
> 一、while循环的基本使用 while循环语句的格式： ***while 循环条件：***
>
> ***循环内容***
>
> ![](.\image\PYTHON\image46.jpeg) 
>  
>
> 与判断语句一样，while循环种也有空格缩进二、while循环的嵌套使用
>
> 通过不同循环的嵌套，可以实现多层循环
>
> ![](.\image\PYTHON\image47.png) 
>  

![](.\image\PYTHON\image48.jpeg)

# for循环

> 2024年7月26日 16:46

![](.\image\PYTHON\image49.jpeg)

![](.\image\PYTHON\image50.jpeg)

![](.\image\PYTHON\image51.jpeg)

> i的临时变量可以是先前就定义出现过的变量，也可以是先前没出现过的变量。
>
> 若临时变量是先去已出现过的变量，那么变量储存的数据将不会被保
> 留，循环结束后，最终在主函数中该变量储存的结果是循环最后一次变量的值。

![](.\image\PYTHON\image52.jpeg)![](.\image\PYTHON\image53.jpeg)

> ![](.\image\PYTHON\image54.jpeg) 
>  

![](.\image\PYTHON\image55.jpeg)

> ![](.\image\PYTHON\image56.jpeg) 
>  

### range循环

> 2024年7月26日 16:46

![](.\image\PYTHON\image57.jpeg)

![](.\image\PYTHON\image58.jpeg)

> range函数的数字范围都是左闭右开的区间

## break和continue

> 2024年7月27日 19:30

![](.\image\PYTHON\image59.jpeg)

> ![](.\image\PYTHON\image60.jpeg) 
>  
>
> ![](.\image\PYTHON\image61.jpeg) 
>  

# 函数基础定义语法

> 2024年7月28日 16:37

![](.\image\PYTHON\image62.jpeg)

> 一、函数的基本定义语法

![](.\image\PYTHON\image63.jpeg)

> ![](.\image\PYTHON\image64.jpeg) 
>  

#### 函数传入参数

> 2024年8月2日 13:40
>
> 二、函数的传入参数

![](.\image\PYTHON\image65.jpeg)![](.\image\PYTHON\image66.jpeg)

> 分区 函数 的第 37 页

# 函数返回值

> 2024年8月2日 13:40

![](.\image\PYTHON\image67.jpeg)

![](.\image\PYTHON\image68.jpeg)

> 特殊返回值none
>
> ![](.\image\PYTHON\image69.jpeg) 
>  

![](.\image\PYTHON\image70.jpeg)

# 函数说明文档（注释）

> 2024年8月2日 14:00
>
> pychram在函数中写下三引号后回车，会自动生成'传入参数'、'返回值'的注释摘要
>
> ![](.\image\PYTHON\image71.png) 
>  

![](.\image\PYTHON\image72.jpeg)

#### 函数嵌套调用

> 2024年8月2日 16:10

![](.\image\PYTHON\image73.jpeg)

> 在同一作用域下，函数的调用无需区分定义的先后顺序例如下图代码是可以执行的，不会报错
>
> ![](.\image\PYTHON\image74.jpeg) 
>  

![](.\image\PYTHON\image75.jpeg)

> 嵌套的函数不会同时执行，而是按代码顺序执行
>
> 分区 函数 的第 41 页

# 函数作用域

> 2024年8月2日 16:27
>
> 一、局部变量与全局变量
>
> ![](.\image\PYTHON\image76.jpeg) 
>  

![](.\image\PYTHON\image77.jpeg)

> 注意，函数内部对全局变量进行修改，并不会影响全局变量在全局的值，只会导致这个变量在函数内部的值被修改
>
> 二、global关键字
>
> 在局部变量前加上global，可以将局部变量声明为全局变量
>
> 如下图示例代码
>
> ![](.\image\PYTHON\image78.jpeg) 
>  

# 多返回值

> 2024年8月3日 21:53

![](.\image\PYTHON\image79.jpeg)

####### 多种参数使用

> 2024年8月13日 14:09
>
> 一、位置参数

![](.\image\PYTHON\image80.jpeg)

> 二、关键字参数
>
> ![](.\image\PYTHON\image81.jpeg) 
>  
>
> 三、缺省参数（默认参数）
>
> ![](.\image\PYTHON\image82.jpeg) 
>  
>
> 四、不定长参数
>
> ![](.\image\PYTHON\image83.jpeg) 
>  

![](.\image\PYTHON\image84.jpeg)

#### 函数作为传入参数

> 2024年8月13日 14:10

![](.\image\PYTHON\image85.jpeg)![](.\image\PYTHON\image86.jpeg)

> 分区 函数进阶 的第 47 页

## lambda匿名函数

> 2024年8月13日 14:09

![](.\image\PYTHON\image87.jpeg)

![](.\image\PYTHON\image88.jpeg)

> 分区 函数进阶 的第 48 页

##### 初识数据容器（类似c中的数组）

> 2024年7月28日 16:38
>
> ![](.\image\PYTHON\image89.png) 
>  
>
> 分区 数据容器 的第 49 页

###### 数据容器：列表（list）

> 2024年8月3日 20:55
>
> 一、列表的定义语法
>
> ![](.\image\PYTHON\image90.jpeg) 
>  
>
> 列表可以一次性储存多种数据，即同一个列表可以混存数据，且可以嵌套

![](.\image\PYTHON\image91.jpeg)

> 二、列表的下标索引
>
> ![](.\image\PYTHON\image92.png) 
>  
>
> 列表可以正取，也可以倒着取，正数和零取出来的是正的顺序，用负数取出来的加上倒着的顺序
>
> 嵌套列表索引：用多个\[\]表示列表索引，第一个\[\]表示第一层列表的位置，第二个\[\]表示第二层的顺序，以此类推，套了几层就用几层中括号
>
> 列表索引数字超出列表范围，会报错，比如一个只有三个元素的列表，是不能取到序号3的，只有序号0，1，2可取
>
> ![](.\image\PYTHON\image93.jpeg) 
>  

![](.\image\PYTHON\image94.jpeg)

> 三、列表的常用操作

1. ![](.\image\PYTHON\image95.jpeg) 
    index方法

> 查询特定元素的下标，输出为正向的索引，查询不到将会报错
> 只能查询一层列表中的值，多层嵌套要直接把前面的层数写好，比如：
>
> *data\[0\].index(x)*
>
> ![](.\image\PYTHON\image96.jpeg) 
>  

![](.\image\PYTHON\image97.jpeg)

2. 修改元素

> ![](.\image\PYTHON\image98.jpeg) 
>  

3. ![](.\image\PYTHON\image99.jpeg) 
    插入
4. 追加元素

![](.\image\PYTHON\image100.jpeg)

> 也可追加多个元素
>
> ![](.\image\PYTHON\image101.jpeg) 
>  

5. 删除

![](.\image\PYTHON\image102.jpeg)

> del可以删除嵌套列表，pop不能删除嵌套列表
> pop具有返回值，返回值为删除的元素
>
> ![](.\image\PYTHON\image103.jpeg) 
>  
>
> remove直接输入具体的元素，会自动搜索匹配对应元素，并将它删除

6. 清空列表

> ![](.\image\PYTHON\image104.jpeg) 
>  
>
> clear不需要输入参数

7. 统计元素出现的次数

![](.\image\PYTHON\image105.jpeg)

8. 统计列表元素数量

![](.\image\PYTHON\image106.jpeg)

> 如果是嵌套列表，则嵌套的列表只会记作一个，不会展开计数四、列表的遍历循环
>
> ![](.\image\PYTHON\image107.jpeg) 
>  
>
> 示例（用while循环）：

![](.\image\PYTHON\image108.jpeg)

> 示例（使用for循环）：
>
> ![](.\image\PYTHON\image109.jpeg) 
>  
>
> ![](.\image\PYTHON\image110.jpeg) 
>  

###### 数据容器：元组（tuple）

> 2024年8月4日 14:07

![](.\image\PYTHON\image111.jpeg)

> 如果强行对元素赋值修改，那么程序会报错，但是有一种特殊情况（见第五点）
>
> ![](.\image\PYTHON\image112.jpeg) 
>  
>
> 一、元组的定义
>
> ![](.\image\PYTHON\image113.jpeg) 
>  
>
> ![](.\image\PYTHON\image114.jpeg) 
>  
>
> 不添加逗号得到的是单元素字符串，不是单元素元组，可以使用type关键字
> 验证

![](.\image\PYTHON\image115.jpeg)

> 二、数据取出

![](.\image\PYTHON\image116.jpeg)

> 定义使用的是小括号（），索引取值使用的是中括号\[ \]
>
> 三、元组常用操作
>
> index查找、count计数、len长度与列表（list）的用法是一致的
>
> ![](.\image\PYTHON\image117.jpeg) 
>  
>
> 四、元组的循环遍历

1. while循环遍历

> ![](.\image\PYTHON\image118.jpeg) 
>  

2. ![](.\image\PYTHON\image119.jpeg) 
    for循环遍历

> 与列表的循环遍历是一样的五、特殊情况
>
> 若在元组内嵌套其他可修改的数据容器，那么是可以对嵌套的内容进行修改的以下以嵌套列表作为示例：
>
> ![](.\image\PYTHON\image120.jpeg) 
>  

### 数据容器：字符串（str）

> 2024年8月4日 14:08

![](.\image\PYTHON\image121.jpeg)

![](.\image\PYTHON\image122.jpeg)

> 值得一提的是，空格在字符串中也会被计入下标下标超出字符串范围，代码也会报错

![](.\image\PYTHON\image123.jpeg)

> 常用操作
>
> ![](.\image\PYTHON\image124.jpeg) 
>  

1. index查询索引

![](.\image\PYTHON\image125.jpeg)

> 使用index查询一串字符在字符串中的位置，将会输出第一个字符的位置

2. replace字符串替换

![](.\image\PYTHON\image126.jpeg)

> 会得到一个替换完成的字符串返回值

3. ![](.\image\PYTHON\image127.jpeg) 
    split分割字符串

> ![](.\image\PYTHON\image128.jpeg) 
>  
>
> 这个方法需要一个输入值

4. ![](.\image\PYTHON\image129.jpeg) 
    strip字符串规整

> 这个函数默认值，默认是去除空格

5. count统计字符出现次数

> ![](.\image\PYTHON\image130.jpeg) 
>  

6. len统计字符串长度

> 返回值是长度
>
> ![](.\image\PYTHON\image131.jpeg) 
>  
>
> 空格也要纳入计算

# 数据容器：序列

> 2024年8月4日 15:13

![](.\image\PYTHON\image132.jpeg)

![](.\image\PYTHON\image133.jpeg)

> 对序列进行切片操作并不会影响序列本身，而是得到一个新的序列，返回值的数据容器类型与进行切片的序列一致，用元组切片，得到的是元组，用列表切片得到是列表

## 数据容器：集合(set)

> 2024年8月4日 15:13

![](.\image\PYTHON\image134.jpeg)

![](.\image\PYTHON\image135.jpeg)

> 集合会自动去掉重复的内容，但是顺序无法保证
>
> 集合常用操作
>
> ![](.\image\PYTHON\image136.jpeg) 
>  
>
> 由于集合是没有顺序的，所以不支持索引查询元素集合与列表一样是支持修改元素的
>
> 1、add添加新元素

![](.\image\PYTHON\image137.jpeg)

> 2、remove移除元素
>
> ![](.\image\PYTHON\image138.jpeg) 
>  
>
> 3、pop取出随机元素 4、clear清空集合
>
> 5、difference取出两个集合的差集(**A-A∩B)**
>
> ![](.\image\PYTHON\image139.jpeg) 
>  
>
> 6、union合并集合

![](.\image\PYTHON\image140.jpeg)

> 7、len统计集合元素个数
>
> ![](.\image\PYTHON\image141.jpeg) 
>  
>
> 8、集合的循环遍历
>
> 集合不支持下标索引，所以不能用while循环遍历，只能用for循环遍历

### 数据容器：字典(dict)

> 2024年8月4日 15:12

![](.\image\PYTHON\image142.jpeg)![](.\image\PYTHON\image143.jpeg)

> 字典中的key是不可以重复的

![](.\image\PYTHON\image144.jpeg)

> ![](.\image\PYTHON\image145.jpeg) 
>  
>
> 字典的常用操作
>
> 1、新增元素和更新元素
>
> ![](.\image\PYTHON\image146.jpeg) 
>  
>
> 2、pop删除元素 3、clear清空元素
>
> ![](.\image\PYTHON\image147.jpeg) 
>  4、keys获取全部的key
>
> 5、通过keys和for循环遍历字典
>
> ![](.\image\PYTHON\image148.jpeg) 
>  
>
> 6、for循环遍历字典
>
> ![](.\image\PYTHON\image149.jpeg) 
>  
>
> ![](.\image\PYTHON\image150.jpeg) 
>  7、len统计字典元素数量

####### 数据容器总结

> 2024年8月5日 20:24

![](.\image\PYTHON\image151.jpeg)

> 分区 数据容器 的第 70 页
>
> 数据容器通用操作
>
> 2024年8月9日 15:02

![](.\image\PYTHON\image152.jpeg)![](.\image\PYTHON\image153.jpeg)

> 字符串转元组和列表的效果是将每一个字符串作为一个元素取出
>
> 字典转列表、元组、集合都是将value丢掉，保留key作为元素，但是转字符串会保留value列表、元组、字符串转集合会删去重复的元素
>
> 分区 数据容器 的第 71 页

##### 字符串大小比较

> 2024年8月13日 13:51
>
> 字符串的比较是基于ASCII码进行比较的

![](.\image\PYTHON\image154.png)

> ![](.\image\PYTHON\image155.jpeg) 
>  

### 文件编码概念

> 2024年8月3日 21:53

![](.\image\PYTHON\image156.jpeg)

![](.\image\PYTHON\image157.jpeg)

> 文件读取
>
> 2024年8月17日 16:47

![](.\image\PYTHON\image158.jpeg)![](.\image\PYTHON\image159.jpeg)

> 一、文件的打开
>
> ![](.\image\PYTHON\image160.jpeg) 
>  

![](.\image\PYTHON\image161.jpeg)

> 文件路径的表示形式：
>
> 在python种文件路径使用'\\''/'都是可以的
>
> open函数中的encoding并不是第三位参数，而是第四位参数，第三位是
> buffering，被忽略了，所以指定编码形式都是使用关键词传参
>
> 二、读取文件的相关操作
>
> ![](.\image\PYTHON\image162.jpeg) 
>  
>
> 对同一个文本连续两次使用read读取的文本会自动衔接，比如第一次
> read读取到了第十个字符，那么第二次read就会从第十一个字符开始
> readlines可以读取换行符号
>
> readline可以读取一行的数据，读取到换行符自动停止，生成含一行数据的列表
>
> 使用for循环读取文件
>
> ![](.\image\PYTHON\image163.jpeg) 
>  
>
> 原理：读取文件时，每一行数据都是作为一个元素，所以每一次读取的都是一行的内容
>
> 三、文件的关闭

![](.\image\PYTHON\image164.jpeg)

> ![](.\image\PYTHON\image165.jpeg) 
>  四、with open语法（自动关闭文件）
>
> 在冒号后面写操作语句，执行完冒号后的所有语句后，文件会自动关闭，有些像函数
>
> 文件写入
>
> 2024年8月18日 11:03
>
> 使用write方法进行文件写入
>
> ![](.\image\PYTHON\image166.jpeg) 
>  

![](.\image\PYTHON\image167.jpeg)

###### 文件追加

> 2024年8月18日 12:29

![](.\image\PYTHON\image168.jpeg)

> 换行写入：只要在需要换行的地方加上"\\n"就行了

![](.\image\PYTHON\image169.jpeg)

> 异常（bug）
>
> 2024年8月18日 12:47
>
> 异常就是bug

![](.\image\PYTHON\image170.jpeg)

> 一、捕获异常
>
> ![](.\image\PYTHON\image171.jpeg) 
>  
>
> 捕获异常的基本语法
>
> ![](.\image\PYTHON\image172.jpeg) 
>  
>
> 捕获指定异常

![](.\image\PYTHON\image173.jpeg)

> 捕获多个异常
>
> ![](.\image\PYTHON\image174.jpeg) 
>  
>
> 捕获所有异常（与基本语法的效果是一样的）
>
> 异常的else语法
>
> ![](.\image\PYTHON\image175.jpeg) 
>  
>
> ![](.\image\PYTHON\image176.jpeg) 
>  
>
> 异常的finally语法

![](.\image\PYTHON\image177.jpeg)

> 二、异常的传递
>
> ![](.\image\PYTHON\image178.jpeg) 
>  
>
> 这意味着，当我们需要检查有层级调用关系的函数异常时，只需要在最高层级（最开始调用的函数）内进行检查就能确定异常类型和位置
>
> 模块概念和导入
>
> 2024年8月18日 14:40
>
> 一、认识模块

![](.\image\PYTHON\image179.jpeg)

> 二、模块的导入方式
>
> 模块的导入一遍会写在代码的最开头
>
> ![](.\image\PYTHON\image180.jpeg) 
>  
>
> 查看模块文件内容的方法，按住CTRL然后点击模块名就可以打开对应模块文件
>
> 导入模块中特定的方法
>
> ![](.\image\PYTHON\image181.jpeg) 
>  

![](.\image\PYTHON\image182.jpeg)

> *import 模块名* 与 *from 模块名 import \**
>
> 如果模块中没有使用\_ \_all\_
> \_变量这两句的效果是一样的，都是导入该模块的所有功能
>
> 自定义模块和导入
>
> 2024年8月18日 14:40

![](.\image\PYTHON\image183.jpeg)

> 需要注意的是自定义的模块文件名要符合python的命名规则
>
> 如果导入了不同模块的同名功能，那么调用的功能将会是最后导入的哪一个，取别名可以避免出现这样的情况
>
> ![](.\image\PYTHON\image184.jpeg) 
>  

![](.\image\PYTHON\image185.jpeg)

> 将模块中的测试代码写在\"*if \_ \_ name \_ \_ ==
> \"main\":*\"之后就可以实现调用模块后不会执行一遍功能函数的代码，而是只在模块单独运行时才会执行代码
>
> ![](.\image\PYTHON\image186.jpeg) 
>  
>
> 原理：\_ \_ name \_ \_ 是python中的内置变量，如果在运行模
>
> 块，那么\_ \_ name \_ \_
> 的内容为main，所以会执行if语句后的所有内容，如果运行一个导入该模块的代码（不是含有测试代码的模块），那么\_
> \_ name \_ \_ 就不等于"main"，所以if语句后的代码不会再执行
>
> **\_ \_ all \_ \_变量**

![](.\image\PYTHON\image187.jpeg)

> python包
>
> 2024年8月18日 14:52

######## 一、自定义包

> python包就是包含了一堆模块的文件夹，特殊的地方在于包含一个名为\_ \_
> init \_ \_.p文件

![](.\image\PYTHON\image188.jpeg)![](.\image\PYTHON\image189.jpeg)

> 在某些编译器（如：python）中创建python package文件夹会自动生成\_ \_
> init \_ \_.p文件
>
> \_ \_ init \_
> \_.p文件的内容可以为空（编译器自动生成的就是空白的），可以不用写内容，但是这个文件必须存在
>
> 建立一个普通的文件夹，然后手动写上\_ \_ init \_
> \_.p文件，也能被识别为一个python包

######## 二、导入自定义包中的模块

> ![](.\image\PYTHON\image190.jpeg) 
>  
>
> 导入时使用**.**来表示层级关系，直接导入文件夹无法使用模块中的功能，必须至少指定到模块
>
> 使用from导入指定到模块
>
> ![](.\image\PYTHON\image191.jpeg) 
>  
>
> 指定到模块中的功能
>
> ![](.\image\PYTHON\image192.jpeg) 
>  
>
> ![](.\image\PYTHON\image193.jpeg) 
>  可以一次性导入多个模块或功能，只要用，（逗号）分开进行

######## 三、python包中的\_ \_ all \_ \_变量

> ![](.\image\PYTHON\image194.jpeg) 
>  
>
> \_ \_ all \_ \_变量是写在\_ \_ init \_
> \_.p文件中的，列表内写上文件夹下的模块名，即可针对import
> \*导入方式导入的模块进行控制
>
> **注意：\_ \_ all \_ \_只对**"from xxx imoprt
> \*"**这种导入方式有用，对于**"import xxx"**是无**

######## 效的

> **四、安装第三方包**

![](.\image\PYTHON\image195.jpeg)![](.\image\PYTHON\image196.jpeg)![](.\image\PYTHON\image197.jpeg)

> 使用pychram进行安装
>
> 右下角配置解释器，进入解释器设置
>
> ![](.\image\PYTHON\image198.jpeg) 
>  
>
> 列表显示的是该python中安装的包有那些，点击左上角的加号就可以搜索对应的包进行安装
>
> ![](.\image\PYTHON\image199.jpeg) 
>  

### 初识方法

> 2024年8月3日 21:53

![](.\image\PYTHON\image200.jpeg)

> 分区 类和对象 的第 91 页

###### json数据格式

> 2024年8月16日 14:17

![](.\image\PYTHON\image201.jpeg)

> 不同的编程语言都有自己的数据格式，java、c/c++、python等不同语言产生的数据格式是不同的，但是json格式的数据是通用的
>
> ![](.\image\PYTHON\image202.jpeg) 
>  
>
> ![](.\image\PYTHON\image203.jpeg) 
>  

![](.\image\PYTHON\image204.jpeg)![](.\image\PYTHON\image205.jpeg)

> pyecharts模块
>
> 2024年8月19日 15:50
>
> 一、基本介绍

![](.\image\PYTHON\image206.jpeg)

> 可以通过网站
> [[gallery.pyecharts.org]{.underline}](http://gallery.pyecharts.org/)查看相关的示例代码和示例图表
>
> 二、绘制折线图
>
> ![](.\image\PYTHON\image207.jpeg) 
>  
>
> 导入pyecharts.charts模块中的Line功能
> 生成Line对象，然后设置x轴坐标和y轴坐标随后设置y轴坐标
>
> 执行render方法可以生成一份折线图的网页文件，使用浏览器打开就可以看到该折线图
>
> 三、全局配置和局部配置
>
> ![](.\image\PYTHON\image208.jpeg) 
>  
>
> 1、全局配置
>
> ![](.\image\PYTHON\image209.jpeg) 
>  

![](.\image\PYTHON\image210.jpeg)

> 在进行全局配置之前需要先导入pyecharts.options模块中对应的各项功能
>
> 例如，标题设置是来自pyecharts.options的TitleOpts
>
> 工具箱设置来自pyecharts.options的ToolboxOpts图例设置来自pyecharts.options的LegendOpts
>
> 映射视图来自pyecharts.options的VisualMapOpts具体可设置的内容可以在网站中查阅
>
> ![](.\image\PYTHON\image211.jpeg) 
>  

# json模块对数据简单处理

> 2024年8月19日 23:31

![](.\image\PYTHON\image212.jpeg)

> 分区 图表 的第 96 页
>
> Numpy
>
> 2024年8月24日 18:43
>
> 一、numpy中的数组
>
> **创建数组**
>
> ![](.\image\PYTHON\image213.jpeg) 
>  
>
> **二维数组、查看数组结构**
>
> ![](.\image\PYTHON\image214.jpeg) 
>  
>
> **索引和切片**（与python基础语法中的序列切片一致）
>
> 如果是一维数组，那么0号元素，就是第一行第一列的单个元素元素
>
> 如果是二维数组，那么单一个0号元素，就是第一行所有元素的序列，a\[0\]\[0\]才是第一行第一列的单个元素元素
>
> ![](.\image\PYTHON\image215.jpeg) 
>  
>
> **基本运算**
>
> \+
> 向量加法（如\[1,2,3\]+\[1,2,3\]=\[2,4,6\]）这点与python基本语法不一致，基本语法中的+表示序列拼接（\[1,2,3\]+\[1,2,3\]=\[1，2，3，1，2，3\]）
>
> \- 向量减法
>
> \* 向量乘法
>
> / 向量除法
>
> **数组形状操作**
>
> reshape变换形状
>
> ![](.\image\PYTHON\image216.jpeg) 
>  
>
> 注意：新形状可容纳的数据量必须与数组的数据量相同，例如一个3x4的矩阵可以变成2x6、4x3，但是不能变成3x3、3x5这样的形状
>
> transpose转置矩阵
>
> ![](.\image\PYTHON\image217.jpeg) 
>  
>
> dot向量点乘、矩阵乘法
>
> ![](.\image\PYTHON\image218.jpeg) 
>  
>
> mean求平均值
>
> ![](.\image\PYTHON\image219.jpeg) 
>  
>
> 调用函数传入数组，与调用数组内部函数是一样的效果
>
> max求最大值 min求最小值
>
> ![](.\image\PYTHON\image220.jpeg) 
>  
>
> std标准差
>
> ![](.\image\PYTHON\image221.jpeg) 
>  
>
> ![](.\image\PYTHON\image222.jpeg) 
>  ![](.\image\PYTHON\image223.jpeg) 
>  sum求和 sort排序
>
> 默认是对每一行进行排序
>
> 如果想对每一个数字都进行排序，可以用reshape，这将会得到一个排好序的列表
>
> ![](.\image\PYTHON\image224.jpeg) 
>  
>
> 筛选（与或非）
>
> ![](.\image\PYTHON\image225.jpeg) 
>  
>
> 判断条件记得打上括号
>
> ![](.\image\PYTHON\image226.jpeg) 
>  
>
> save保存数组
>
> ![](.\image\PYTHON\image227.jpeg) 
>  
>
> ![](.\image\PYTHON\image228.jpeg) 
>  loads导入数组 random随机数使用
>
> linespace线性数组数据生成
>
> 如图是生成一个0到10，均匀分布为的10个数据
>
> ![](.\image\PYTHON\image229.jpeg) 
>  
>
> x内容为
>
> ![](.\image\PYTHON\image230.jpeg) 
>  
>
> Pandas
>
> 2024年8月24日 18:44
>
> 一、excel文档阅读
>
> ![](.\image\PYTHON\image231.jpeg) 
>  
>
> ![](.\image\PYTHON\image232.jpeg) 
>  使用head函数，可以查看excel前几行的内容，默认是前五行

![](.\image\PYTHON\image233.jpeg)

> excel文件读取
>
> ![](.\image\PYTHON\image234.jpeg)
>
> 将excel文件保存为csv文件
>
> ![](.\image\PYTHON\image236.jpeg) 
>  
>
> csv文件读取
>
> ![](.\image\PYTHON\image237.jpeg) 
>  
>
> ![](.\image\PYTHON\image238.jpeg) 
>  csv文件保存为excel文件读取tab键分隔的文本
>
> ![](.\image\PYTHON\image239.jpeg) 
>  
>
> 略过前几行读取文件

![](.\image\PYTHON\image240.jpeg)

> ![](.\image\PYTHON\image241.jpeg) 
>  json文本读取
>
> 二、dateframe数据类型
>
> pandas提供的数据类型，可以与excel表格转换，用字典可以转换成dateframe
>
> ![](.\image\PYTHON\image242.jpeg)
>
> 三、series数据类型

![](.\image\PYTHON\image244.jpeg)

> ![](.\image\PYTHON\image245.jpeg)
>
> series数学函数（基本运算）
>
> 对series使用基本运算会使每一个值都做相应运算，比如a+100会使a中的数据都加上100

![](.\image\PYTHON\image247.jpeg)

> ![](.\image\PYTHON\image248.png) 
>  
>
> idmax、idmin最大、最小值的下标索引

![](.\image\PYTHON\image249.jpeg)

> ![](.\image\PYTHON\image250.jpeg)
>
> unique输出不重复的一个集合 numique输出集合有几个数
> counts能统计某个数出现几次

![](.\image\PYTHON\image252.jpeg)

> 四、info查看基础信息
>
> ![](.\image\PYTHON\image253.jpeg) 
>  
>
> 五、dropna缺失值处理
>
> ![](.\image\PYTHON\image254.jpeg) 
>  
>
> dropna会删除有不完整数据的那一行
>
> 六、数据类型转换
>
> ![](.\image\PYTHON\image255.jpeg) 
>  
>
> 使用astype转化成需要的数据类型
>
> 七、索引
>
> 一列数据索引
>
> 类似于字典的查询，使用变量名后中括号中写上行数据的key，就可以定位到那一列的数据
>
> 例如
>
> ![](.\image\PYTHON\image256.jpeg) 
>  
>
> 单个数据索引
>
> 类似于二维数组，第一个中括号写列的key值，第二个中括号写行上行数，就可以精确定位到期望的一个数据
>
> ![](.\image\PYTHON\image257.jpeg) 
>  
>
> 八、筛选功能
>
> 类似于numpy中数组的筛选，如下图的代码就是筛选出所有等于1的值，用df_1储存
>
> ![](.\image\PYTHON\image258.jpeg) 
>  

# Matplotlib

> 2024年8月24日 18:44
>
> ![](.\image\PYTHON\image259.jpeg) 
>  以matplotlib中最常用的pyplot为例
>
> plot绘图
>
> ![](.\image\PYTHON\image260.png) 
>  
>
> ![](.\image\PYTHON\image261.png) 
>  
