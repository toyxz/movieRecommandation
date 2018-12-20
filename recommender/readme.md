# Simple Recommder Algorithm

## 1.tag-based (item-knn)
基于标签的推荐算法。电影数据共有27个标签。
推荐结果：找到和用户的喜好标签最匹配的k部电影

## 2. user-knn
基于用户协同过滤的推荐算法。每个用户都会有评分向量（评分取值为1-5）。
推荐结果：找到和该用户的评分习惯最相近的k个用户，从这k个用户评分过的电影中推荐。