# Textcnn_tensorflow

基于搜狐2019算法赛数据的细粒度情感分析

data文件夹存放的是数据以及停用词表

model文件夹存放训练好的模型文件

word2vec文件夹下是训练好的词向量模型，用的是这次比赛的训练集和测试集共同训练。

data_process.py用于数据预处理

textcnn_model.py是textcnn的模型代码

train.py是训练代码

下载下来直接运行train.py文件，就可以训练模型

如果需要改动以适应于自己的数据，主要需要修改train.py里面的参数设置部分

此次代码中还有很多需要完善的地方，将在今后的学习中继续完善

关于模型更详细的介绍可以查看本人的csdn博客：https://blog.csdn.net/weixin_43256799/article/details/90647107

本人初学者一枚，所以可能有写错的地方还望指出
