# 包
## 包的安装
`install.packages("car")`
*建议在线安装，不建议本地安装*

## 包的加载
`library(caret)`
### 单独加载包内的某个函数
`car::vif()`

## 更新包
`update.packages()`
*更新所有包，逐个提示*
*更新指定包，以包名称作为参数即可*

## 移除包
`remove.packages()`
***
# 获取帮助
## 获取某个函数的帮助
`?help`
`help("libary")`
## 某个关键词的帮助
`??help`
`help.search("libary")`
# 某个package的帮助
`help(package = "ggplot2")`
# 获取当前工作目录
·getwd()`
## 设置工作目录
`setwd(" *文件地址* ")`
***文件地址中使用斜杠/而非反斜杠\，反斜杠\为转义字符***
## 获取文件路径
`file.choose()`
***
# Rstudio的项目（工程）创建
***
# 保存R文件.Rdata
*直接鼠标点击*
`save()`
`save.image()`
# 加载某个包内置的数据集
`data()`
# 列示当前环境中的对象
`ls()`
# 移除某个对象
`rm()`
# 移除所有对象
`rm(list = ls())`
***
# R常用数据类型
## 数值型
123
2.34
## 字符型
“Hello, world.”
'123'
## 逻辑型
TRUE
T
FALSE
F
# 判断 函数名（参数名=参数值）
`is.numeric(123)`
`is.numeric(FALSE)`
`is.character('123')`
`is.logical('123')
`is.logical(FALSE)`
# 转换
`as.numeric('123')`
`as.numeric('转换')`
`as.numeric(T)`
`as.numeric(F)`
`as.character(123)`
`as.logical("Hello,world")`
`as.logical(2)`
`as.logical(1)`
`as.logical(-2)`
`as.logical(2.1)`
`as.logical(0)`
# 特殊值
NA
`is.na(NA)`
NULL
`is.null(NULL)`
NaN
`is.nan(Nan)`
Inf
-Inf
`is.infinite(-Inf)`
# 示例
2/0
-2/0
0/0
***
# R常用数据结构
## 赋值
***对象名 <- 对象值***
*快捷键：alt+-*
*=用于函数中为参数取值*
## 向量
### 常量
pi
letters
LETTERS
month.name
month.abb

*C()函数用于连接*
*seq(from=,to=, by=)函数用于生成一段顺序数据*
*rep(,times=)函数用于重复某个变量*
*length.out可用于seq函数中用于规定生成数据长度*

## 强制转换为同一类型的数据
c(t,"aic")

## 向量元素名称
names(V2)
names(v2) <- v9

## 向量长度
length(v9)
## 向量索引
v8[3]
v8[c(1,3,5)]
v8[-c(1,4)]
v2[c('aic',icp')]
v1[v1%%2==1]
*%%余数函数，==是否相等*
