# position-encoding-and-representation-theory
解释如何从齐性空间表示论的角度直接导出各种position encoding，比如旋转位置编码，球谐位置编码，图的Laplace位置编码。

# fundamental formulation
有几何对象X(比如Rn代表词向量的嵌入空间，S2表示二维球面，H表示图)，有群G作用在X上（比如Z作用在Rn上表示词的平移，SO(3)作用在S2上表示旋转，Sn作用在H上表示label置换），还有一个新的表示空间，即位置编码空间Y，
满足<x,y>=<f(x),f(y)>=<f(gx),f(gy)>,在rope里面第二个等式表示注意力权重（语义）的相对位置不变性，数学上是说G在Y的作用是第一个等式表示注意力权重的前后不变性，为了得到2=3，我们发现1=2是说f是X上的G-不变函数，1=3
