# 下载安装

直接在官网下载R语言官网软件，然后下载Rstudio

# R语言数据类型

## 基本类型

### numeric（数字型）

类型：整型（int）、浮点型（double）

如果不指定数据类型，那么默认数据类型就double型

```R
b<-2 #赋值为2.0
a<-2L #赋值为整数2
```

### character（字符型）

字符串

```R
l="今天下雨了"
```

### logical（逻辑型）

布尔型(ture or false)

```R
a<-T 
```

### vector向量

**c()** 是一个创造向量的函数

```R
a<-c(1,2,3)
```

### list列表

```R
list.a<-(a=1,b="今天天气不错"，c=1+3i)
view（list.a）# 查看列表a
```

### Date Frame数据框

类似excel表格，用于展示二维数据

```R
table = data.frame(
    姓名 = c("张三", "李四"),
    工号 = c("001","002"),
    月薪 = c(1000, 2000)
   
)

print(table) # 查看 table 数据

str(table)# 获取数据结构

print(summary(table))  # 显示概要

result <- data.frame(table$姓名,table$月薪)
print(result)# 提取指定的列

# 扩展数据框
# 添加部门列
table$部门 <- c("运营","技术","编辑")

# 合并两个数据框
result <- rbind(table,newtable)
print(result)

# 创建向量
sites <- c("Google","Runoob","Taobao")
likes <- c(222,111,123)
url <- c("www.google.com","www.runoob.com","www.taobao.com")
# 将向量组合成数据框
addresses <- cbind(sites,likes,url)


```

### Matrix矩阵

```R
matrix(data = NA, nrow = 1, ncol = 1, byrow = FALSE,dimnames = NULL)
参数说明：

data 向量，矩阵的数据
nrow 行数
ncol 列数
byrow 逻辑值，为 FALSE 按列排列，为 TRUE 按行排列
dimname 设置行和列的名称
```

## 基本语法

赋值运算

```R
a<-1
```

函数

```R
函数名（参数）
is.intger(a)
```

as强制类型转换

```R
a<-as.integer(1) #强制将1.0转换成整型赋值给a
```
