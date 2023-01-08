## 2、HTML5 基本语法 

　　与HTML4相比， HTML5在语法上发生了很大的变化。为了确保兼容性，HTML5根据Web标准，重新定义了一套在现有HTML基础上修改而来的语法，以便各浏览器在运行HTML的时候能够符合通用标准。下面具体介绍在HTML5中语法进行了哪些改变。

#### 　　1、内容类型

　　HTML5的文件扩展名和内容类型保持不变。例如，扩展名仍然为".html"或"htm"，内容类型(ContentType)仍然为"text/html"。

#### 　　2、文档类型

　　DOCTYPE命令声明文档的类型 ，它是HTML文档必不可少的组成部分，且必须位于代码的第一行。

　　在HTML5中，可以不使用版本说明，一份文档将会适用于所有版本的HTML。在HTML5中，文档类型的声明方法如下：<!DOCTYPE html>

 　当使用工具时，也可以在DOCTYPE声明中假如SYSTEM识别符,声明方法如下：<!DOCTYPE HTML SYSTEM "about:legacy-compat">

　　在HTML5中，DOCTYPE声明方式是不区分大小写的，引号也不区分单引号还是双引号。

#### 　　3、字符编码

　　在HTML5中 ，继续沿用meta元素定义文档的字符编码，但是简化了charset属性的写法:<meta charset="UTF-8">

　　**从HTML5开始，对于文件的字符编码推荐使用UTF-8。**

#### 　　4、标记省略

　　在HTML5中，元素的标记可以省略。具体来说，元素的标记分为3种类型: 不允许写结束标记、可以省略结束标记、开始标记和结束标记全部可以省略。下面简单介绍下这3种类型各包括哪些HTML5新元素。

1. 不允许写结束标记的元素有: area、base、br、col、command、embed、hr、img、input、keygen、link、meta、param、source、track、wbr。
2. 可以省略结束标记的元素有：li、dt、dd、p、rt、rp、optgroup、option、colgroup、thead、tbody、tfoot、tr、td、th。
3. 可以省略全部标记的元素有：html、head、body、colgroup、tbody。

