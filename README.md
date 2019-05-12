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
        
        > 不懂那就[百度一下](http://www.baidu.com)\
            不懂那就[百度一下](http://www.baidu.com "百度")

    * 参考式
   
        参考式超链接一般用在学术论文上面，或者另一种情况，如果某一个链接在文章中多处使用，那么使用引用 的方式创建链接将非常好，它可以让你对链接进行统一的管理。

        ```
            我经常去的几个网站[谷歌][Google_lnk]、[百度][baidu_lnk]以及[Ｇithub][Ｇithub_lnk]

            [Google_lnk]: www.google.com "Google"
            [baidu_lnk]: www.baidu.com "百度" 
            [Ｇithub_lnk]: https://github.com/
        ```
        显示效果：
        >我经常去的几个网站[谷歌][Google_lnk]、[百度][baidu_lnk]以及[Ｇithub][Ｇithub_lnk]

        [Google_lnk]: www.google.com "Google"
        [baidu_lnk]: www.baidu.com "百度" 
        [Ｇithub_lnk]: https://github.com/
        
    * 自动链接
        
        Markdown 支持以比较简短的自动链接形式来处理网址和电子邮件信箱，只要是用<>包起来， Markdown 就会自动把它转成链接。一般网址的链接文字就和链接地址一样。

        比如：`<http://example.com/>`和`<http://example.com/>`

        > <http://example.com/>　和　<http://example.com/>

    
4. **锚点**
    
    用HTML方式
    `<span id="jump">跳转到的地方</span>`

    > <span id="jump">跳转到的地方</span>
        [点击跳转](#jump)

    　或者直接转跳标题目录：[基本编辑](#1、基本编辑)

5. **列表**
    * 无序列表
     
        使用 *　+　- 表示无序列表
         
    * 有序列表

        有序列表则使用数字接着一个英文句点

    * 定义型列表

        定义型列表由名词和解释组成。一行写上定义，紧跟一行写上解释。解释的写法:紧跟一个缩进(Tab)
       
## 2、快捷键

        
- [Markdown-Note](#markdown-note)
  - [1、基本编辑](#1%E5%9F%BA%E6%9C%AC%E7%BC%96%E8%BE%91)
  - [2、快捷键](#2%E5%BF%AB%E6%8D%B7%E9%94%AE)
