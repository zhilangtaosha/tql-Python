1）userid和itemid交互后，也就是用户对物品的评分矩阵，这时候就可以使用itemcf或svd等等；

2）把不同用户的itemid的点击序列作为训练样本，使用word2vec，对itemid进行embeding。