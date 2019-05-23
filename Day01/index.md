## Day01 - 初识Python

### Python简介

- 1994.01: 发布 Python 1.0 (彼时小李还没一岁...)
- 存在的缺点: 代码无法加密
- 多行注释: 三个引号开头，三个引号结尾

```Python
"""
向伟大的 Dennis M. Ritchis 先生致敬

Version: 0.1
Author: Gaga
"""

print('hello world!')
```

### 其他工具介绍

- 安装 `IPython`

```Shell
pip3 install ipython jupyter
```

- 安装 `anaconda`

### 练习

1. 翻译 Python 之禅

```Python
import this

Beautiful is better than ugly.
Explicit is better than implicit.
Simple is better than complex.
Complex is better than complicated.
Flat is better than nested.
Sparse is better than dense.
Readability counts.
Special cases aren't special enough to break the rules.
Although practicality beats purity.
Errors should never pass silently.
Unless explicitly silenced.
In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
Although that way may not be obvious at first unless you're Dutch.
Now is better than never.
Although never is often better than *right* now.
If the implementation is hard to explain, it's a bad idea.
If the implementation is easy to explain, it may be a good idea.
Namespaces are one honking great idea -- let's do more of those!
```

翻译如下：
```
Beautiful is better than ugly
美丽优于丑陋

Explicit is better than implicit.
直率优于遮掩

Simple is better than complex.
简单优于复杂

Complex is better than complicated.
复杂优于晦涩

Flat is better than nested.
扁平优于嵌套

Sparse is better than dense.
疏松优于密集

Readability counts.
可读性很重要

Special cases aren't special enough to break the rules.
Although practicality beats purity.
虽然实用性胜过纯洁性，但特例并没有重要到可以破坏规则

Errors should never pass silently.
Unless explicitly silenced.
除非你确认需要这么做，否则所有的错误都不能静悄悄的掩盖

In the face of ambiguity, refuse the temptation to guess.
There should be one-- and preferably only one --obvious way to do it.
面对模棱两可的情况时，拒绝猜测，并尽量去寻找一种显而易见的或许是唯一的最佳方法去解决

Although that way may not be obvious at first unless you're Dutch.
这并不是一件容易的事情，除非你是 Python 之父

Now is better than never.
Although never is often better than *right* now.
现在就做好过永远不做，但是不做总比不考虑马上就做要更好

If the implementation is hard to explain, it's a bad idea.
如果方案并不容易阐述，那就是个怀方案

If the implementation is easy to explain, it may be a good idea.
如果你的方案很容易阐述，那就是个好方案

Namespaces are one honking great idea -- let's do more of those!
命名空间是一个绝佳的理念 -- 让我们更多的发挥它吧！
```

2. 绘制图形