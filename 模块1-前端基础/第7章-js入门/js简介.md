

# 第一部分 
1. JavaScript简单介绍（配7.1html）
* JavaScript的组成：
    * ECMAScript（5.1）：JavaScript组成言的语法和基本对象
    * DOM：文档对象模型，描述处理网页内容的方法和接口
    * BOM： 浏览器对象模型，描述与浏览器进行交互的方法和接口
* JavaScript特点：
    * 跨平台的web脚本语言
    * 向html添加交互行为
    * 可与服务器进行通信

* JavaScript出现的位置
    * 行间
        ```html
        <iuput type="button" onclick="alert(1);" value="Click"/>
        ```
    * 内嵌
        ```html
        <script>
            //这里是JavaScript代码
        </script>
        ```     
    * 外链js文件
        ```html
        <script src="demo.js"></script>
        ```

2. JavaScript实例（配7.2html）
* 实例
    *需求：
        1. 点击页面当中的按钮,按钮背景色改为黄色
        2. 点击页面中的按钮，改变div的宽度与高度