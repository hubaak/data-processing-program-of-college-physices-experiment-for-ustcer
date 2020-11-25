#大物实验数据处理器 for ustcer
## Intro
”大物实验，我**妈！“，这是每个ustcer在做完每周一次的大物后以及当周末还要花1~2小时处理数据的时候从内心深处发出的呐喊。鉴于部分实验不确定度计算时出现较多复杂的导数运算，我每次处理数据的时候都写了个mathematica小程序以方便计算。这里会更新目前为止的大物实验数据处理程序。
>比如下面的这个复杂导数一看就不是给人算的
$$
\frac{\text{d0} \text{n0} \sin (\text{$\theta $0}) \left(1-\sin ^2(\text{$\theta $0})\right) \cos (\text{$\theta $1}) \cot (\text{$\theta $1})}{\text{d1} \sqrt{\frac{1-\sin ^2(\text{$\theta $0})}{\text{n0}^2-\sin ^2(\text{$\theta $0})}} \left(\text{n0}^2-\sin ^2(\text{$\theta $0})\right)^2 \left(1-\frac{\text{d0} \sin (\text{$\theta $0}) \csc (\text{$\theta $1}) \left(1-\sqrt{\frac{1-\sin ^2(\text{$\theta $0})}{\text{n0}^2-\sin ^2(\text{$\theta $0})}}\right)}{\text{d1}}\right)^3 \sqrt{\frac{\cos ^2(\text{$\theta $1})}{\left(1-\frac{\text{d0} \sin (\text{$\theta $0}) \csc (\text{$\theta $1}) \left(1-\sqrt{\frac{1-\sin ^2(\text{$\theta $0})}{\text{n0}^2-\sin ^2(\text{$\theta $0})}}\right)}{\text{d1}}\right)^2}+\sin ^2(\text{$\theta $1})}}
$$
