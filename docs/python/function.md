### 常用内置函数集合
> isinstance() 函数来判断一个对象是否是一个已知的类型，类似 type()
>>isinstance(object, classinfo)
```
    #判断change是否为datetime.datetime类型
    if isinstance(change, datetime.datetime):
        return True
    else:
        return False
```  
***
> enumerate() 函数用于将一个可遍历的数据对象(如列表、元组或字符串)组合为一个索引序列，同时列出数据和数据下标
>>enumerate(sequence, [start=0])  start为下标起始位置，不配置则默认从0开始
```
    #遍历数组内容和序号
    getlist=[a,b,c]
    for x, change in enumerate(getlist):
    print(x,change)
    # 0,a
    # 1,b
    # 2,c
```