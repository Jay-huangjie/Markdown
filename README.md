# markdowm-demo
## 这个文件是专门练习和展示Markdown语言用的,只要认真看多敲几遍，markdown很容易上手
****
###  Author:jay-huangjie
###  Email:289223562@qq.com
****
## 目录
 * [基本样式](#基本样式)
 * [标题写法](#标题写法)
 * [文本内容](#文本内容)
      * 普通文本             
      * 高亮文本     
      * 斜体              
      * 粗体                     
 * [加入图片](#加入图片)
 * [使用列表](#使用列表)
      * 有序列表
      * 无序列表
      * 复选框列表  
 * [代码高亮](#代码高亮)
 * [使用表格](#使用表格)
 * [使用表情](#使用表情)
## 正文 
```
小技巧：markdowm语言中的空格都是有作用的，一般使用一个符号后都要加入一个空格才会起作用,一般至少输入两个空格键才会换行，
一个TAB键==4个空格键，切换到下一行后最好打个空格再编写,这样它不会自动跳到上一行去,如果发现使用了标识符却发现不起作用,
就多打几行与上文隔开并对齐,或者发现样式错乱就缩进空格与正文对齐试试,一般大多数错误都是空格引起的
```
### 基本样式
```
  下划线：***，___ ,--- 都可以产生下划线效果,注意：一个标识符是不行的哦，要多输入几个
```
*****

_____


-----


### 标题写法

```
 #一级标题  ##二级标题  以此类推.... 最高六级标题
```
 # 一级标题
 ## 二级标题
 ### 三级标题
 #### 四级标题
 ##### 五级标题
 ###### 六级标题
 
### 文本内容
```
 普通文本直接输入即可,不用加入任何标识符,高亮文本需要在文本前后加入```，对于单独的高亮文本块,只需将文本单独包裹即可，例如
 `这是单独的一个高亮文本`
```
 这是一行普通文本
 
 ```
   这是一段高亮文本
 ```
 `这` `是` `单` `独` `的` `文` `本` `块`
----------------------------------------
 使用特殊字体
 
|语法|效果|
|----|----|
|`*斜体1*`|*斜体1*
|`_斜体2_`|_斜体2_
|`**粗体1**`|**粗体1**
|`__粗体2__`|__粗体2__
|`***斜粗体1***`|***斜粗体1***
|`___斜粗体2___`|___斜粗体2___
|`~~删除线~~`|~~删除线~~
|`~~***斜粗体删除线***~~`|~~***删除线***~~

#### 这三种特殊字体都可以混合使用
#### 这种语法逻辑很简单，不知各位看官是不是找出了记忆的规律呢
 ---------------------------------
### 加入图片
  #### 展示图片
`````
  语法：![alt](URL title) ,alt表示图片加载失败时替换的文本,URL为图片的路径,也可以是图片的下载地址,title为鼠标悬停是显示的图片文本,注意要加"",alt   和title为非必填。
  forExample:
  ![我是图片加载失败时显示的文本](https://github.com/Jay-huangjie/README-demo/edit/master/README.md "图片文本")
``````

  #### 展示链接
`````
    文字链接与图片链接语法就相差了一个`!`号 ：[alt](URL title),alt为展示的文字,URL为点击文字跳转的链接,title为鼠标悬停时显示的文字。
`````

### 使用列表
`````
操作如下
 * [基本样式](#基本样式)
 * [标题写法](#标题写法)
 * [文本内容](#文本内容)
      * 普通文本             
      * 高亮文本     
      * 斜体              
      * 粗体                     
 * [加入图片](#加入图片)
 * [使用列表](#使用列表)
      * 有序列表
      * 无序列表
      * 复选框列表  
 * [代码高亮](#代码高亮)
 * [使用表格](#使用表格)
 * [使用表情](#使用表情)
`````
 ### 使用表格
 ```
 |语法|效果|
|----|----|
|`*斜体1*`|*斜体1*
|`_斜体2_`|_斜体2_
|`**粗体1**`|**粗体1**
|`__粗体2__`|__粗体2__
|`***斜粗体1***`|***斜粗体1***
|`___斜粗体2___`|___斜粗体2___
|`~~删除线~~`|~~删除线~~
|`~~***斜粗体删除线***~~`|~~***删除线***~~
```
 
 
 
 
