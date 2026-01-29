目的：简单的txt已经无法满足数据存储的需求

json是一种清晰的文本规范，可以记录树形数据

json可以记录四种常规的类型，字符串，数组，布尔型，null

如何在VS中引入json
在官方GitHub下选择single include（集成发布的，不要选择没有single的，我就错在这里）
另一个错误，我在使用json这个文件的时候，头文件不能用<>，因为这是在默认路径下进行的，而要用“”从改路径开始

从json中学到的一些东西
json数组也是一种可迭代数组，所以可以用for（declaration:range）来访问所有内容
要求range必须得要有.begin().end()才能访问
