# HTML入门笔记1
这是我的一篇HTML入门学习笔记。主要写的是关于我在饥人谷HTML入门课程中所学到的关于HTML的知识。
## HTML简介
HTML(HyperText Markup Language),超文本标记语言，一种用于创建网页的标准标记语言。由物理学家蒂姆·伯纳斯-李在欧洲核子研究中心（CERN）在承包工程期间发明。随着时间的不断推移和该语言的不断发展，该语言已经日趋成熟并在web开发中占据了重要的地位。
## HTML起手式
通常我们在编写HTML文档时，都应当包含以下起手式：
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>

<body>

</body>

</html>
```
这一连串代码中，为浏览器制定了这个页面的文档类型，声明了当前HTML文档所使用的HTML版本，指定了我们所使用的字符编码类型。
## HTML的各类标签
通过学习我了解到HTML中包含了各式各样的标签，其中就包括了章节标签以及内容标签。
###章节标签
章节标签主要用于表示文章的层级，主要包括有：
1. h1~h6：主要是用于表示文章的标题，可分为1至6级标题。
2. section：用于表示开始了一个新的章节
3. article:用于表示文档、页面、应用或网站中的独立结构，其意在成为可独立分配的或可复用的结构。​​
4. main:用于标记主要内容。
5. aside:用于标记旁支内容。
###内容标签
内容标签主要是用于表示内容属性的标签。主要包括有：
1. ol+li：用于表示一个有序列表。
2. ul+li：用于表示一个无序列表。
3. em：表示对一段内容的强调。
4. code：用于表示该段内容是一段代码段。
5. a:用于超链接。
##全局属性
通过方方老师的讲解，我还了解到HTML中的一些所有标签都拥有的全局属性：
* class：主要是用于对各式标签进行分类，标记该标签。
* hidden：主要用于标签的隐藏，使其处于不可视状态。
* style：用于制定某标签样式的HTML属性，与css中的style有所不同。
* tabindex：该属性主要用于确定其所在标签是否可以聚焦，以及它是否/在何处参与顺序键盘导航。# notes-of-HTML-1