# GBDT\(Gradient Boosting Decision Tree\)

又称 Multiple Additive Regression Tree,GBDT中的树都是回归树  
GBDT算法基树采用CART回归树，树节点的划分指标是平方损失函数，叶子节点的值是落在该叶子节点所有样本的目标均值。树与树之间的Boosting逻辑是：新树拟合的目标是上一课树的损失函数的负梯度的值。GBDT最终的输出结果是将样本在所有树上的叶子值相加。

