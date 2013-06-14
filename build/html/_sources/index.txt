Pelican
=======

Pelican 是一个用 Python_ 实现的静态网站生成器。

* 用您选定的编辑器( 如： vim_ )直接写出您的内容，支持 reStructuredText_ ， Markdown_ ，和 AsciiDoc_ 格式
* 包含一个简单的命令行工具用以(重新)生成您的站点
* 可方便地与分布式版本控制系统和网络钩子配合使用
* 完全静态输出，可托管在任何地方

特性
----

Pelican 当前支持：

* 文章(如：博客帖子)和页面(如：“关于”，“项目”，“联系方式”)
* 评论，通过一个外部服务( Disqus_ )实现。(请记住：Disqus 很有用，但它是一个外部服务，因此评论数据将会多少有点脱离您的控制，同时潜在地存在数据丢失的可能性。)
* 主题支持(主题是用 Jinja2_ 模板创建的)
* 用多种语言发表文章
* Atom/RSS 供稿
* 代码语法高亮
* 文章/页面生成PDF (可选的)
* 从WordPress，Dotclear，或者RSS源导入
* 集成外部工具，如：Twitter，Google Analytics等 (可选的)

Why the name "Pelican"?
-----------------------

"Pelican" is an anagram for *calepin*, which means "notebook" in French. ;)

Source code
-----------

You can access the source code at: https://github.com/getpelican/pelican

Feedback / Contact us
---------------------

If you want to see new features in Pelican, don't hesitate to offer suggestions,
clone the repository, etc. There are many ways to :doc:`contribute<contribute>`.
That's open source, dude!

Send a message to "authors at getpelican dot com" with any requests/feedback! You
can also join the team at `#pelican on Freenode`_ (or if you don't have an IRC
client handy, use the webchat_ for quick feedback.

Documentation
-------------

A French version of the documentation is available at Pelican_.

.. toctree::
   :maxdepth: 2

   getting_started
   settings
   themes
   plugins
   internals
   pelican-themes
   importer
   faq
   tips
   contribute
   report
   changelog

.. Links

.. _Python: http://www.python.org/
.. _vim: http://www.vim.org/
.. _reStructuredText: http://docutils.sourceforge.net/rst.html
.. _Markdown: http://daringfireball.net/projects/markdown/
.. _AsciiDoc: http://www.methods.co.nz/asciidoc/index.html
.. _Disqus: https://disqus.com/
.. _Jinja2: http://jinja.pocoo.org/
.. _`Pelican documentation`: http://docs.getpelican.com/latest/
.. _`Pelican's internals`: http://docs.getpelican.com/en/latest/internals.html
.. _`#pelican on Freenode`: irc://irc.freenode.net/pelican
.. _webchat: http://webchat.freenode.net/?channels=pelican&uio=d4
.. _Pelican: https://pelican.readthedocs.org/en/latest/fr/index.html
