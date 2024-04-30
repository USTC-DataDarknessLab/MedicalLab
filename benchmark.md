Medical NLP

命名实体识别、词性标注、归一化，有现成的第三方库，不需要神经网络

医学是一门独立的语言，甚至由于领域知识过于庞杂，任何一个子领域可能使用独立的语言

Text Classification Benchmark

2018 BERT

2019

[SpanBert：对 Bert 预训练的一次深度探索 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/75893972) 不只是span，还有基于span边界预测指定位置的监督

[T5 模型：NLP Text-to-Text 预训练模型超大规模探索 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/88438851) Google出品，大量实验，大量结论，可用于指导调参

2021

[SimCSE论文解读 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/369075953) 句子嵌入sota，但不一定利于下游任务

[无监督对比学习SIMCSE理解和中文实验操作-CSDN博客](https://blog.csdn.net/HUSTHY/article/details/119971673) 细节

[Sentence-T5｜谷歌提出文本表示新SOTA (qq.com)](https://mp.weixin.qq.com/s/Ed-qlaQj2zvTMv8-T-grCg) 双塔结构，多加了一层投影和L2-Norm

注意：有监督对比loss上的temperature=100，之前无监督对比学习的T都很小



