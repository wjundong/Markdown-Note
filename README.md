# Markdown-Note

## 1、基本编辑

1. **粗体和斜体**
   
   源代码：
    ```
        *斜体*或_斜体_
        **粗体**
        ***加粗斜体***
        ~~删除线~~
    ```
   

    显示效果：

     >*斜体*或_斜体_\
        **粗体**\
        ***加粗斜体***\
        ~~删除线~~


2. **分级标题**
   * 第一种写法：
        ```
            这是一级标题
            ================
            这是二级标题
            ----------------
        ```

   * 第二种写法：
        ```
        # 一级标题
        ## 二级标题
        ### 三级标题
        #### 四级标题
        ##### 五级标题
        ###### 六级标题
        ```
3. **超链接**
   
   Markdown 支持两种形式的链接语法： 行内式和参考式两种形式，行内式一般使用较多。
    * 行内式：
        
        ```
            [链接文字](链接地址 "title属性")    注：title属性可加可不加

            不懂那就[百度一下](http://www.baidu.com)

            不懂那就[百度一下](http://www.baidu.com "百度")
        ```
        显示效果：
        
        >不懂那就[百度一下](http://www.baidu.com)\
            不懂那就[百度一下](http://www.baidu.com "百度")

4. **参考式**   
    参考式超链接一般用在学术论文上面，或者另一种情况，如果某一个链接在文章中多处使用，那么使用引用 的方式创建链接将非常好，它可以让你对链接进行统一的管理。
    ```
        我经常去的几个网站[Google][1]、[Leanote][2]以及[自己的博客][3]
        [Leanote 笔记][2]是一个不错的[网站][]。

        [1]:http://www.google.com "Google"
        [2]:http://www.leanote.com "Leanote"
        [3]:http://http://blog.leanote.com/freewalk "梵居闹市"
        [网站]:http://http://blog.leanote.com/freewalk
    ```
    显示效果：
      我经常去的几个网站[Google][1]、[Leanote][2]以及[自己的博客][3]
        [Leanote 笔记][2]是一个不错的[网站][]。\
        [1]:http://www.google.com "Google"
        [2]:http://www.leanote.com "Leanote"
        [3]:http://http://blog.leanote.com/freewalk "梵居闹市"
        [网站]:http://http://blog.leanote.com/freewalk

## 2、快捷键


