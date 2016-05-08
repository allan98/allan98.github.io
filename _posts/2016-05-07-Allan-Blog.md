---
layout: post
title: "Allan's Blog-从搭建开始！"
date: 2016-05-07 15:11:23
tags: [jekyll, sublime, bundle, bootstrap]
---

看了很多GitHub搭建博客的网络资料，对于一个新手来说，信息量很大，慢慢摸索着一步一步前行。搭建过程虽然曲折，但对学习新知识来说，是值得的。

+ GitHub & Jekyll
+ Jekyll-Bootstrap 
+ Markdown
+ Sublime
+ Git

## # GitHub & Jekyll介绍
Git是一个分布式的版本控制系统。Github作为开源代码库以及版本控制系统，只支持Git作为唯一的版本库格式进行托管，已经成为了管理软件开发以及发现已有代码的首选方法。在GitHub，用户可以十分轻易地找到海量的开源代码。Github也为码农提供了一个博客系统，叫做Github Pages。GithubPages可以被认为是用户编写的、托管在Github上的静态网页。

>推荐阅读这一系列有关Git的文章,讲得深入浅出,生动有趣:<http://www.worldhello.net/gotgithub/01-explore-github/010-what-is-github.html>

Jekyll是一个静态站点生成器，它会根据网页源码生成静态文件。它提供了模板、变量、插件等功能，可以用来生成整个网站。利用Jekyll先在本地编写符合Jekyll规范的网站源码，然后上传到Github，由Github生成并托管整个网站。

>GitHub Pages is deeply integrated with Jekyll, a popular static site generator designed for blogging and software documentation, but used for much more. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers some other advanced templating features.

## # 学习Jekyll方法推荐官方文档

>Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll 官网文档部分翻译](http://blog.csdn.net/maoxunxing/article/details/40479753)

[jekyll]: http://jekyllrb.com
[jekyll-gh]: https://github.com/mojombo/jekyll

## # 搭建GitHub Blog
阮一峰:搭建一个免费的，无限流量的Blog----[github Pages和Jekyll入门](http://www.ruanyifeng.com/blog/2012/08/blogging_with_jekyll.html)

[使用Jekyll在Github上搭建个人博客](http://www.tuicool.com/articles/INBnMz)

[Jekyll在github上构建免费的Web应用](http://blog.fens.me/jekyll-bootstarp-github/)

## # 语法高亮
[Jekyll 语法高亮的格式](http://jekyllrb.com/docs/posts/#highlighting_code_snippets)

[GitHub 语法高亮的格式](https://help.github.com/articles/github-flavored-markdown)

Jekyll 代码高亮的[几种选择](http://www.2cto.com/kf/201602/489968.htm)

{% highlight ruby %}
def show
    @widget = Widget(params[:id])
    respond_to do |format|
        format.html # show.html.erb
    format.json { render json: @widget }
    end
end
{% endhighlight %}

## # Markdown 
[语法说明 (简体中文版](http://www.appinn.com/markdown/#list)

## # Bootstrap
人气极高的bootstrap项目，这是一个非常强大的CSS框架，你可以访问它的[项目主页](https://github.com/twbs/bootstrap)，点“Fork”就在自己的账号下克隆了一个bootstrap仓库。

更新中。。。
