# **学习markdown笔记**

## _我认为标记语言中重要的部分_

## 重点标记

### 1.字体、颜色
+ **<font color=yellow>黄色</font><font color=green>蓝色</font>**
+ **<font face="华文彩云">华文彩云字体</font>**
+ <table><tr><td bgcolor=#F6F7F8>背景色白色</tr></table>

```
<font color=yellow>红色</font><font color=green>蓝色</font>
<font face="华文彩云">华文彩云字体</font>
```
### 2.格式

#### 段首缩进

 ```
shift + 空格(改变成全角)
__ __#### 段首缩进
 ``` 
### <p align="center">可以用以下格式</p>
 ```
 <p align="center">可以用以下格式</p>
 
 ``` 
 ### <p align="center">其中公式可用</p>

 $$z = ax + by\tag{1}$$
 ```
 $$z = ax + by\tag{1}$$
 $$ $$代表单独一行的公式，\tag{1}才是公式右边的{1}
 ``` 
## 3.图表
    1. 形成列表 
       1. 分列如 * 和 + 在演示中都影响到下一行，所以换行就要两个Enter  
       2. 无序格式“ -、+、* ”都行 
    2. 甘特图
    3. 流程图
    4. 数据图
    5. 表格
   
* |学号|姓名|成绩|
|:-:|:-:|:-:|
|1|1|1|
#### 格式为
```  
|学号|姓名|成绩|
|:-:|:-:|:-:|
|1|1|1|
```
## 4.导入
### 1.图片

> _我的图片_

<img src="https://s1.ax1x.com/2020/03/17/8aJAbR.jpg" width="20%" height="20%" align="right">

```
图片格式：图片标题![你的图片备注](url)
```
~~别人的图片~~
*缺点是不能改大小*

---
简单网址格式<https://s1.ax1x.com/2020/03/17/8aJAbR.jpg>

**可以改大小的图片格式**

```
图片格式：<img stc="url" width="100%" height="100%" align="left">
```
<img src="https://s1.ax1x.com/2020/03/17/8aJAbR.jpg" width="15%" hight="15%" align="middle">

### 2. 网址：
   ```
   []("title")
   ```
## 其他格式
* ### 选择框
* [x] 是
* [ ] 否
```
* [x] 是
* [ ] 否
```
* ### 分割线1 ***

***

* ### 分割线2 ---

--- 

* ### <u>下滑线</u>
```
<u>....</u>
```
 * ### 区块引用
>区块引用：一行一竖线
>>可以嵌套引用
>
>可以跳过一个空行使区块不断开
但是有内容连在一起的就会连在一起，而且同一块可以只用一个“>”
```
> 区块引用：一行一竖线
>>可以嵌套引用
>
>可以跳过一个空行使区块不断开
但是有内容连在一起的就会连在一起，而且同一块可以只用一个“>”
```  

* ### 代码格式
1. “~~~” 或 “ ``` ”
2. 空四格或一个Tab
~~~python
print("hallo world!")
~~~
    一个tab空格也可以得到以上效果
也可以有`printf("hallo world")`行内代码

* ### 格式套用
- 列表项目套用格式如：
    > 有引用
    ##### 等其他格式
        列表中的代码段
* ### 格式避免
/1. 可以避免不需要的列表
- 还用可以用代码框避免格式
- 一般格式的后两行就可以摆脱格式限制，它们具有分块的特性

总结：通过[markdown例子](https://www.zybuluo.com/mdeditor)进行模仿，[印象笔记Markdown](https://list.yinxiang.com/markdown/eef42447-db3f-48ee-827b-1bb34c03eb83.php)和[简单语法说明](https://www.appinn.com/markdown/)可以加快理解学习