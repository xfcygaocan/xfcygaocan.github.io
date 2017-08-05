---
layout: post
title: 个人博客搭建及使用
date: 2016-02-15 15:32:24.000000000 +09:00
---
==========================分割线==========================
## 用Jekyll搭建的Github Pages个人博客
### 先占坑

==========================分割线==========================
## 常用命令
### 解析器
添加markdown解析器，在_config.yml里添加
{% highlight markdown %}
markdown: kramdown
{% endhighlight %}

### 字体
{% highlight markdown %}
**黑体**
{% endhighlight %}
{% highlight markdown %}
*斜体*
{% endhighlight %}
{% highlight markdown %}
<del> 删除体 </del>
{% endhighlight %}

### 分隔线
{% highlight markdown %}
* * *
{% endhighlight %}
{% highlight markdown %}
{% endhighlight %}
{% highlight markdown %}
***
{% endhighlight %}
{% highlight markdown %}
- - -
{% endhighlight %}
{% highlight markdown %}
---
{% endhighlight %}

### 引用
{% highlight markdown %}
> 这里是引用
{% endhighlight %}

### 列表
有序列表项前加数字和点（注意前后面要空格）
{% highlight markdown %}

1. 列表1

2. 列表2

{% endhighlight %}

### 表格
{% highlight markdown %}
|水果名称|价格（元/500克）|
|:-------:|-----:|
|苹果|3.2|
|香蕉|4.5|
{% endhighlight %}

### 插入代码
{% highlight python %}
def main():
    print('hello world')
{% endhighlight %}

### 数学公式
行内
{% highlight markdown %}
$$E=mc^2$$
{% endhighlight %}

行间
{% highlight markdown %}
$$
a_{i}
$$
{% endhighlight %}

### 插入图片
存在渲染慢的问题
{% highlight markdown %}
![test](.png "Title")
{% endhighlight %}
{% highlight markdown %}
<img src=".png" height="100%" width="100%">
{% endhighlight %}

### 脚注
{% highlight markdown %}
比如[^f1]
[^f1]: 脚注1
{% endhighlight %}

### 插入链接
{% highlight markdown %}
[Jekyll’s GitHub repo][4]
[4]:   https://github.com/jekyll/jekyll
{% endhighlight %}
{% highlight markdown %}
[baidu](http://www.baidu.com)
{% endhighlight %}

### Reference

[用Markdown写blog的常用操作][1]  
[Jekyll中使用MathJax][2]  
[Jekyll中文文档][3]  
[用Jekyll搭建的Github Pages个人博客] [4]

<!-- 链接 -->
[1]: http://www.cnblogs.com/mo-wang/p/5117819.html
[2]: http://pkuwwt.github.io/linux/2013-12-03-jekyll-using-mathjax/
[3]: http://jekyllcn.com/
[4]: http://louisly.com/2016/04/used-jekyll-to-create-my-github-blog/
