# relationclassification
FewRel 1.0 text entity relation classification, 
N-way K-shot meta-learning

## 参考
1. FewRel: A Large-Scale Few-Shot Relation Classification Dataset with State-of-the-Art Evaluation 
https://github.com/thunlp/FewRel

##项目

* Fewrel_ProtoNet_CNN.ipynb：
参考train_demo.py 实现
对FewRel数据集，batchsize多个Nway Kshot任务，word/position embedding，一层CNN编码，protoNet分类

## data
* train_wiki.json FewRel关系分类训练集合
* val_wiki.json FewRel关系分类验证集合