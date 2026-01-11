# adversarial-fraud-dialogue-detection
Course project: Adversarial data rewriting for fraud dialogue detection

# 对抗性数据改写在欺诈对话检测中的应用

本项目为课程大作业，主要研究对抗性数据改写方法对欺诈对话检测模型性能的影响。

## 项目内容
- 使用传统机器学习模型（SVM）和预训练语言模型（BERT）进行欺诈对话分类
- 基于对抗性文本改写方法构造对抗样本
- 对比分析原始数据集与对抗样本数据集上的分类性能变化
- 通过消融实验分析不同改写策略的影响

## 实验环境
- Python 3
- PyTorch
- Transformers
- Scikit-learn
- Google Colab

## 代码说明
- `fraud_detection.ipynb`：模型训练、对抗样本生成与实验分析代码

## 说明
数据集因课程要求未公开上传，仅提供代码用于方法复现。
