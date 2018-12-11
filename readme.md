本文是对word2vec + textRank的方法进行了一次整合，然后写出的一个文章自动摘要算法。

本代码应用于中文，英文文章请修改语料处理部分即可。


processCorpus：   处理语料

wordvec：        获得Word2vec模型

textRank：       运用textRank算法获得topN句子

由于word2vec模型太大，所以未上传，需要自己训练。语料随便copy一篇新闻即可。效果感觉一般，以后还会改进，
