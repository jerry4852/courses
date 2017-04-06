# 开源项目简介

各位小伙伴大家好，咱们接着前面的课程，继续讲解 Github 开源之旅第六季：how-to-markdown。现在咱们讲解开源项目简介这个话题。

GitHub 这个全球最大的开源社区上面托管的项目可多了去了，我们看到 GitHub 给出的官方数据，截至 2016 年年底，GitHub 上托管的项目数量达到三千多万个。在这么庞大数量的项目中我们很多新手都蒙圈了，项目太多了，无从下手，想参与项目不知道自己能做点儿什么。这恐怕是很多新手刚接触开源社区时，都会面临的问题。在这里我们有必要跟小伙伴们介绍一下开源软件或项目的情况，主要是介绍一下开源软件和项目的分类，让小伙伴们有个宏观的把握，来指导自己的项目实践。

## 语言角度

对开源项目分类的最直观、最简单的角度就是语言的角度。也就是说这个项目或者这个软件是用什么编程语言开发的。

【打开 GitHub 网站 workshopper 组织页面】
我们看到每个项目仓库下面都有一个带颜色圆点，圆点的右侧写着这个项目所使用的语言。当然，可能一个项目会用多种语言混合开发，这个项目上显示的圆点是权重最大的语言。我们也看到文档行项目仓库所使用的语言是没有标示的，其实就是 MarkDown 语言。

【进到 learnyounode 仓库页面】
我们看到这个仓库页面下面，有一个彩色的横条，当我们点击这个彩色横条的时候，我们看到这个项目实际使用的编程语言有三种：HTML、CSS 和 JavaScript，以及这三种语言在项目中所占的比例。当然，HTML 语言用的最多，所以项目列表上只显示 HTML。而且，每种语言的颜色编码是固定的。

这样，我们在参与开源项目的时候，我们就可以选择自己熟悉的编程语言的项目来参与了。

## 规模角度

另一个比较直观和简单的分类方法就是：规模。对于代码规模我们最常用的衡量参数就是代码行数。这个开源软件项目是个几十行、几百行的微型项目，还是个几千行的小项目，还是上万行的中型项目，还是几十万行的大型项目，甚至是上百万行的超大型项目。我们用代码行数来评价项目规模。

对于初学者，我们一般都喜欢从一些规模小的项目下手，这样我们理解起来不太困难，参与这样的项目也不用花太多的时间和精力。这样的项目在 GitHub 上有吗？当然有，而且还不少，就怕我们很多小伙伴看不上眼。

GitHub 没有非常直观和简单的办法让我们来快速评估一个代码仓库的规模。一般可以采用的方法是在 GitHub 网站，在仓库页面中看一个仓库目录中代码文件的数量，如果文件夹以及文件数量比较多，那么这个项目比较大。反之，则比较小。如果相比较精确的衡量项目的代码行数，我们可以把整个项目克隆到本地，然后用代码分析工具来分析项目规模。更简单的办法是我们直接通过 Shell 脚本来分析代码行数。

给大家举个例子。

## 其他角度

