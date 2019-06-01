- ##### 将命令执行后的结果赋值给变量
```shell
x=`ls`
echo $x
```
- ##### 使用grep精确匹配某个（单）词，用于精确查找
```shell
x=`ls | grep -w w50.l50`    # 参数 -w 不可省略
echo $x
```
