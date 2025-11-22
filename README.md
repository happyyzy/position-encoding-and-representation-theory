# position-encoding-and-representation-theory
解释如何从齐性空间表示论的角度直接导出各种position encoding，比如旋转位置编码，球谐位置编码，图的Laplace位置编码。本文假设读者对表示论有基本的了解。

# fundamental formulation
所有位置编码都是在构造一个齐性空间上的不变/等变函数，用表示论的知识可以迅速推出一般的框架，我们一个个例子来看。

这个一般的框架有助于在保证不变/等变的前提下对位置编码做可能的优化，比如qwen3-vl使用的交错式3DRoPE。

github的markdown写着太恶心，pdf文件如下：

[rope](rope.pdf)

[拉普拉斯位置编码](Lap.pdf)

[球谐位置编码](SPE.pdf)




