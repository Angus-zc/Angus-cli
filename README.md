Angus-cli ---> 搭建组件开发模板的脚手架

还有可以扩展的地方有：
1. 增加更多情况的判断，比如要创建的目录有重复文件夹名，首先询问是否删除文件夹
2. 增加对更多模板的支持，create-vue的做法是首先定义一些模板，放到一个template
    目录下面，然后根据用户输入的条件，将template下对应的模板复制到项目对应目录下面。