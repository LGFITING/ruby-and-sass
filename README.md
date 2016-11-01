#本文档只为记录ruby and sass的安装
#ruby download: http://www.ruby-lang.org/en/downloads/ 安装点选path
#ruby -v && gem -v查看版本
#安装ruby后之后采用git clone的方法下载sass
#sass clone 地址：git clone git://github.com/nex3/sass.git
#sass 安装命令： gem install sass
#查看命令：sass -v
#编译命令 sass sass.scss cass.css
#编译后引入html

#关于注释
标准的CSS注释 /* comment */ ，会保留到编译后的文件。
单行注释 // comment，只保留在SASS源文件中，编译后被省略。
在/*后面加一个感叹号，表示这是"重要注释"。即使是压缩模式编译，也会保留这行注释，通常可以用于声明版权信息。
