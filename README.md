# Decision Trees & PCA Analysis

本项目包含了三个实验代码，分别使用了 Iris 数据集和乳腺癌（Breast Cancer Wisconsin）数据集，来演示决策树分类和 PCA 降维在模型中的应用。除此之外，还提供了决策树结构的可视化示例代码。

## 目录

- **Problem 1:**  
  使用 Iris 数据集，构造不同最大深度的二元决策树，并比较 Recall、Precision 和 F1 Score。
  
- **Problem 2:**  
  使用乳腺癌离散数据集构建深度为 2 的决策树，并计算首个节点的 Entropy、Gini 和 Misclassification Error，分析信息增益及选择的特征和分割值。
  
- **Problem 3:**  
  使用乳腺癌连续数据集，在决策树建模前进行 PCA 降维，分别使用 1 个和 2 个主成分构造模型，并对比模型性能（F1 Score、Precision、Recall 以及混淆矩阵）。
  
- **Visualize Tree:**  
  提供一个额外的脚本，用于导出并可视化决策树的结构（依赖 graphviz 和 pydot）。

## 依赖

- Python 3.x
- pandas
- scikit-learn

额外依赖（仅用于决策树可视化）：
- graphviz
- pydot

安装依赖：

```bash
pip install -r requirements.txt
