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
