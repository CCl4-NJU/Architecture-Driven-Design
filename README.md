# Architecture-Driven-Design

迭代踩坑后的经验

1-3可以直接仿照例子来写，就不说了

第4大步中：

1.找关注点

我做的时候是先考虑之前的ASR里面分别属于哪些质量属性类别，然后它的子关注点就按照tactics来拆分，比如某个ASR它属于Availability的部分，那就先用自然语言把这个ASR到底是个啥需求给描述出来，然后它的子关注点就分割为不同的tactics范畴来描述，比如Availability的tactics有fault detect，fault preparation and fixed等四类tactics，那就将当前的ASR，分为可以用fault detect来解决的子任务1、能用fault preparation and fixed来解决的子任务2等，这些个子任务就是所谓的子关注点，具体可以参照第一次迭代。

2和3

这两个部分尽量写到一起，这样每列完一个ASR子关注点的表马上就能写结论，不用上下移来移去找。此处尽量先把子关注点多的给写了，这样后面就能大量复制粘贴。。



4.根据例子很好理解



5.视图

module就是静态模块视图，我理解的是大模块和大模块之间的依赖关系（还有继承啥的，不过感觉用的不多）

c&c就是动态交互视图，主要就是说大模块里的各个小模块之间怎么交互，怎么依赖的

software element视图好像可选，主要就是把迭代前对子系统的再分解的那些个部件加上ADD过程中增加的那些pattern联系起来，参考ppt就行



第5大步

这个地方我觉得就是把module视图里的各个模块职责给描述一下



第6大步

大概写一写，接口声明啥的不用太齐全，意思意思。。。



以上提到的例子指的就是我第一次迭代的文档结果。