# 1、词向量与ELMO模型

## 1、基础部分
词的表示：通过量化的形式来表示一个单词
###1、one-hot编码 <无法表示单词之间语义的相似度>
我们： [1,0,0,0,0,0]
爬山:  [0,0,1,0,0,0]

###2、词向量
向量的降维<T-SNE>

学习词向量：
输入<文档>  -> 模型 -> 词向量

模型： CBow、SkipGram、NNLM、Glove、ME、ELMo、LDA

###3、语言模型：
判断是否一句话从语法上通顺
对于句子的计算

w1,w2,w3,w4,w5
w1 -> w2
w1,w2->w3
w1,w2,w3 -> w4

相关知识点：chain rule,Markov Assumption, 
Unigram,bigram,ngram
add-one smoothing,good-turning Smoothing, 
preplexity

基于分布式表示的模型总览
![Image text](imageordmodel.bmp)

建议的学习路径
![Image text](imageordpath.bmp)
























