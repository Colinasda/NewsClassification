## 问题定义
新闻标题分类

## 数据集说明
10911017.txt是数据集，all_content和all_label是代码中切割完数据集后自动生成的txt文件

## 模型使用
* Naive Bayes
* KNN（遍历K从1到14）
* SVM（4种核函数）
* Decision Tree
* Random Forest

## 评价标准
使用5折交叉验证，取mean accuracy作为评价指标
