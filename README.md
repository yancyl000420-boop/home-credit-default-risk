# Home Credit Default Risk - 信用违约预测

## 项目背景
基于 Kaggle 竞赛数据，预测贷款申请人违约概率。

## 技术方案
- 模型: LightGBM
- 可解释性: SHAP
- 验证 AUC: 0.7610

## 关键发现
- EXT_SOURCE 系列外部信用评分为最重要的预测特征
- 单样本 SHAP 分析可清晰解释模型决策逻辑

## 文件说明
- `notebook.ipynb`: 完整代码与分析
- `shap_feature_importance.png`: 全局特征重要性
- `shap_waterfall_sample.png`: 单样本解释示例

## 运行环境
Kaggle Notebook (Python 3.12)

## 参考
- [Kaggle Competition](https://www.kaggle.com/c/home-credit-default-risk)
