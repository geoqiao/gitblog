# [From English Import Python](https://github.com/geoqiao/gitblog/issues/13)


## 关于我
我是一个很普通的人，大学在普通二本商科专业。

刚毕业的时候vlookup都不会，到熟练excel；后来因为公司数据中台做的特别烂，自己学了SQL，从杂乱的底表自己捞数，最后自己一个人维护整条业务线的数据库视图层（当然工资没有涨，只是事情变多了）

在跳槽做策略分析后，发现日常工作仍然有好多东西并不是能从数据库来的，SQL 和 Tableau 并不能解决全部问题。

每个月仍要处理大量杂乱无章的excel工作，这消耗我很多精力，工作非常痛苦。

于是萌生了学习Python的想法，通过半年多通勤路上、周末晚上的阅读学习，现在已经写了两个脚本，原来每天半小时的工作量，现在只需要一次点击，3秒钟完成。

但还是有很多 Python 方法不熟悉不知道、很多方法的参数不熟悉不知道、很多需求不知道怎么表达怎么Google。

所以，我创建了这个 [repo]() ，来记录我的学习过程。

并且，如果我都能学会，那只要你也感兴趣这个，你也可以学会。

## 数据源
大部分数据源应该来自[kaggle](https://www.kaggle.com/datasets), Kaggle是一个免费的数据集网站，同时有很多课程，如果想要做一些数据分析项目，可以在 Kaggle 寻找合适的数据集。

但是，kaggle的数据源真的质量太高了，感觉好像没有人被我工作中的那种数据折磨过。

所以之后，我会增加一些我平时工作会遇到的数据作为数据源（当然会脱敏处理一下），

## 学习资源推荐
### Python基础
必须是[CS50P](https://youtube.com/playlist?list=PLhQjrBD2T3817j24-GogXmWqO5Q5vYy0V)

从最简单的概念和问题开始学起，去解决最难的问题。最开始我是看国内教程的，但是他们一上来 `print('hello world')`之后，就开始数据结构、循环、条件语句，真的太难听懂了，很劝退。

大卫老师从简单的问题讲起，让我理解数据结构、循环、条件语句是如何解决我们碰到的问题的。写出有bug的代码也没关系，尝试跟着大卫老师一起思考代码哪里有问题，我们想解决什么问题，如何利用Python去解决这个问题。

### 数据分析库
必须是这个[Udemy课程](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/)

Data Science？没有关系，里面讲的pandas、seaborn、matplotlib真的很好，有兴趣可以看后面的机器学习部分，没兴趣就别看了，在一开始学那么难没有必要。

在这里，老师会手把手教你写代码，每节课都会有课后练习在[github](https://github.com/SuvroBaner/Python-for-Data-Science-and-Machine-Learning-Bootcamp)，一定要去亲自手敲一边，哪怕是一边看答案一边敲。

### 书
必须是[Python for Data Analysis: Data Wrangling with Pandas, NumPy, and IPython](https://wesmckinney.com/book/)

作者本身就是pandas的作者，写的也非常好。我看的是第二版，第三版已经放在网站上公开校对，主要针对新的pandas版本做了更新。

我建议可以不用过于介意pandas版本，可能你学了2.0版本的pandas，但是实际上公司用的还是1.0版本。最开始也不用一页一页去读，翻看一边目录，挑选pandas相关章节简单看一看，最重要的是不要一开始给自己太高目标，自己把自己劝退。

### 文字版教程
微软[Python for beginners](https://learn.microsoft.com/en-us/training/paths/beginner-python/?WT.mc_id=academic-77958-bethanycheum)：

实际上，我并不觉得这个教程对于学习Python有多好，但他足够简单，简单到我是抱着学习英语的心态看这个教程的。

### 练习
最重要的还是练习，我不会建议你把教程中所有的代码都跟着老师敲一边，因为那真的很劝退人。一边看视频、一边敲代码、一边点暂停播放，光想想就觉得太反人类了。上课的时候认真听，听完消化一下，再尝试自己敲一敲。当然，敲不了也没有关系，有时间再敲，但是一定要敲。

[Udemy课程](https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass/)的GitHub页面有课后习题，也有习题答案；微软[Python for beginners](https://learn.microsoft.com/en-us/training/paths/beginner-python/?WT.mc_id=academic-77958-bethanycheum)甚至不需要你自己安装Python环境，直接在教程网页就可以跑练习代码。其他的教程可以自己安装Python环境后，使用VSCode一起跟着敲。

### 配置Python环境
配置Python环境真的太令人头痛了，我一开始通过Homebrew安装，结果安装了好几个版本，刚开始学也不会建立虚拟环境，体验真的糟糕。而且我很爱折腾，Python一有新版本我一定要第一时间`brew upgrade`。最后，我想这样是不行的。

所以我在这里推荐Anaconda。Anaconda是一个用于科学计算的Python发行版，它包含了众多常用的科学计算和数据分析工具，例如NumPy、Pandas、SciPy、Matplotlib等等，下载安装都很简单。也省去了安装各种包的麻烦。

最大的优点就是简单，简单是最大的优点。

## 最后
最好的学习不是一开始就能学会很难的东西，而是从简单的看起，一步一步持续进步。

如果一个人跟小白讲怎么开始自学机器学习，一开口就各种算法怎么牛逼，那我建议尽早结束谈话。他这么讲只有两个原因，要么他很无知在吹牛逼，要么他不是一个很好的老师。

建立自信是极为重要的，武侠小说的主人公，都是都打败恶势力的一个小兵开始的，要是一开始碰见大boss，那早就完蛋了。