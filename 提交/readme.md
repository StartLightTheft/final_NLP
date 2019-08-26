#项目运行环境

colab notebook

Linux 操作系统

特征提取，普通CPU，25G RAM
训练BERT模型，TPU，12G RAM
训练XGB模型，GPU，12G RAM

#使用的库

numpy
pandas
sklearn
sciPy
tqdm
time
pickle
matplotlib
bayes_opt
gensim
tensorflow
tensorflow hub
nltk

#训练时间

基准模型 bert ：1个小时

最终XGB模型：23分钟

#代码说明

由于时间仓促，代码没有来得及整理，某些代码块没有来得及删除，因此无法直接按顺序运行。

但是用到的代码都在这里了。

data preprocessing包括文本的清理、stemming、lemmatizing、去除stop words

feature 相关的notebook 都按照对应的特征类别命名。

naive model包含最初的比较模型

finetun model glv 是主要的调试notebook

data convert 是前期预处理有些问题，在这个notebook解决了。