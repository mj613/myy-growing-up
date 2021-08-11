# 这是一级标题
## 这是二级标题
### 这是三级标题

**加粗了**

*倾斜了*

***斜体加粗***

~~删除了~~

>这是引用的内容
---
>>这是2次引用的内容
***
>>>这是3次引用的内容

***
图片

![图片alt](https://17english.com/static/img/home1.e8b9340b.png "课堂宝")


[百度](http://baidu.com)

1. 列表内容
2. 列表内容
3. 列表内容

注意：序号跟内容之间要有空格

列表嵌套

上一级和下一级之间敲三个空格即可

    一级无序列表内容
        二级无序列表内容
        二级无序列表内容
        二级无序列表内容

        表头|表头|表头
        |---|:--:|---:
        内容|内容|内容
        内容|内容|内容

        第二行分割表头和内容。
        - 有一个就行，为了对齐，多加了几个
        文字默认居左
        -两边加：表示文字居中
        -右边加：表示文字居右
        注：原生的语法两边都要用 | 包起来。此处省略

        姓名|技能|排行
        |--|:--:|--:
        刘备|哭|大哥
        关羽|打|二哥
        张飞|骂|三弟      

'单行代码'

(''')
//代码块
public ResponseData<int> Close()
+        {
+           ResponseData<int> result = new ResponseData<int>();
+            result.Code = 0;
+            currentMainWindow.Close();
+            return result;
+        }

| Tables| Are | Cool |
| ------------- |:-------------:| -----------------:|
| col 3 is | right-aligned | $1600 |
| col 2 is | centered| $12 |
| zebra stripes | are neat very long long |$1111111111111111 |
