项目一：2D 材料薄片检测与分类系统（基于 OpenCV + GMM）
项目简介
本项目旨在实现二维材料（如 Graphene 和 WSe₂）薄片图像的自动检测与分类，主要基于 OpenCV 图像处理与 GMM（高斯混合模型）聚类算法进行分析。项目支持科研图像批量处理，可应用于材料制备前期筛选工作中。

项目功能
图像对比度特征提取

背景建模与图像分割

GMM 聚类实现图像中材料区域识别

支持批量处理科研图像数据集

技术栈
Python 3.10

OpenCV

scikit-learn

Jupyter Notebook

项目二：有机酸分子 pKa 预测建模（基于 Python + 机器学习）
项目简介
本项目基于公开 pKa 数据集，使用 RDKit 生成分子结构特征（指纹和描述符），并构建随机森林模型预测有机酸的 pKa 值。模型具有良好的可解释性与泛化能力，可扩展至其他分子性质建模任务中。

项目功能
SMILES 转分子指纹与描述符（Morgan、MACCSKeys、RDKit）

随机森林回归模型训练与预测

超参数调优（GridSearchCV）

SHAP 可解释性分析

与基准模型和公开网站结果对比验证

技术栈
Python 3.12

RDKit

Scikit-learn

SHAP

Pandas, Matplotlib
