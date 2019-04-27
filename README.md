# Python学习笔记
### Python中的string
- string是个常量
- string的操作有：
 > 1. \<string\>.split() : 分解string
 > 2. \<string\>[-1] : string中的最后一个字符
###Python中的list
- list中可以有list等等一系列元素
- list的操作函数有：
 > 1. \<list\>.append(\<value\>) :在list尾部添加value
 > 2. len(\<list\>):list的长度 
 > 3. \<list\>.index(\<value\>)  : 查找到value则返回值的索引，没查找到则返回error 
 > 4. \<value\> in \<list\> : 如果value在list中显示true,否则显示false
>  5. \<value\> not in \<list\> : 跟上面结果相反
>  6. \<list\>.pop() :移除list中最后一个元素并返回它
> 7. \<list\> + \<list\> :生成一个新的list而不是在第一个list后append第二个list

### 一些函数
>- ord(\<value\>) : value应该是一个Ascii字符,把value转换成Ascii值
>- chr(\<value\>) : value应该大于等于0小于等于255，把value转换成Ascii字符
>- range(start, end[,step]) : 生成从start(包含)到end(不包含)的列表

### 使用爬虫需要的注意事项
>- 注意礼仪
  > 每个域名的robats.txt文件会告诉你多久能爬取一次
>- 如何用多台计算机同时进行爬取
  > 多台计算机同时爬取时如何避免对同一个域名的重复爬取
>- 如何充分利用大量带宽，不浪费资源
