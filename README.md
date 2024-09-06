# 项目简介
在本文中，我们将使用pySpark中的 MLlib 构建一个端到端的机器学习模型。我们将使用来自 kaggle 上的[Home Credit Default Risk](https://www.kaggle.com/c/home-credit-default-risk/overview)竞赛的真实数据集。本次竞赛的目的是根据从每个申请人收集的数据来确定贷款申请人是否有能力偿还贷款。目标变量为 0（能够偿还贷款的申请人）或 1（无法偿还贷款的申请人）。这是一个二元分类问题，目标标签高度不平衡。分配率接近 0.91 到 0.09，其中 0.91 是能够偿还贷款的申请人的比例，0.09 是无法偿还贷款的申请人的比例。

# 项目内容
## 数据预处理
先简单了解下数据集
![overview](https://github.com/Glocas-Leonardo/Photo/blob/a2db8cf63e09e6cdb64437b49b15679a1b9bf86e/overviewdf.png)

目标变量的分布情况
![label](https://github.com/Glocas-Leonardo/Photo/blob/a2db8cf63e09e6cdb64437b49b15679a1b9bf86e/lable.png)
