---
layout: post
title: Period Mappings and Period Domains
tagline: James Carlson, Stefan Müller-Stach, Chris Peters
categories: [日拱一卒]
---

这本书和最近的任务有关，需要的部分是6，7，8章，关于Generic Torelli for Hypersurfaces。读完之后我想过一下4，5之后看一下第三部分。几何的东西我不太熟，感觉还是有念一下的必要。这本书本身在网上没有公开资源，所以我也不在这里放出了。

---

2025/12/22 第6章 纸版P194-210

大致浏览了一下，基本是我已熟知的内容。倒不能细节非常清楚，但是这种东西不自己写而是读的话应该还是搞不懂的。第一遍读的话还是理解直觉为主吧。一点收获是发现之前有个记混了，导出的推出是保持hypercohomology的。然后一个比较有意思的东西是relative log form，这个和取极限应该是有关系的。我之前考虑的最简单的模型是$ \mathbb{C}^{*}  $，是一条开的曲线，那么这个的baby model就是$ \mathbb{C}  $带上原点，要求singular locus是simple normal crossing的。最简单的一个例子是hyperplane arrangement，但直觉这应该是多了一点奇点出的信息，换句话说是这个arrangement本身而不是补集上的信息。这么说来，Gauss-Manin本身是regular的，这好像就直接看出来了？ 那可能baby model不是很有意思，但还是可以考虑和arrangement有关的模空间。

---

2025/12/26 7.1-7.2 纸版P212-217

看的我火大。今天的内容是比较技术性的关于Koszul complex和regularity的内容，但是书中的求和范围却完全没有标注，导致的结果是完全猜不出来准确的定义，没有定义还怎么往下看啊。我觉得可能要翻一下Voisin看她怎么处理这段代数细节的，Wiki上的表述记号差的比较远。

说到记号，这本书自己前后记号都不一样，module和sheaf的Koszul cohomology定义差一个变量替换，真是绷不住了。搞明白了之后自己写一遍吧。

---

2025/12/29 7.3-7.4 纸版P218-226

Wiki神力让我稍微有点感觉。对于regularity，一个比较清晰的定义如下：$ \mathbb{P}^{n}  $上coherent sheaf $ \mathcal{F} $被称为$ m $-regular，若任给$ i > 0 $均有
<center>   
$$
    H^{i}(\mathbb{P}^{n},\mathcal{F}(m-i)) = 0.
$$ 
</center> 
从定义中没法直接看出来的是，$ m $-regular能推出$ (m+1) $-regular。这里书里面给的证明又是模糊不清。它说是Koszul sequence tensor $ \mathcal{F} $之后得到exact的complex，但怎么看这都不对啊？或许它是指大于$ 0 $的部分exact，但这样代数的引理还对吗？我觉得需要仔细check一下。

然后看了一下Macaulay定理和Donagi's Symmetrizer Lemma的描述，完全没有感觉。我感觉不如先看几何的部分？我不太清楚这几个引理在几何上的应用。但是鉴于代数引理的方法可能有本质作用，我还是算一算吧。