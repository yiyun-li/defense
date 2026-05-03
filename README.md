# SLE Model Principles Interactive Page

这是一个用于毕业答辩展示的静态交互页面，内容基于论文 `Materials and Methods` 中的八个 SLE 风险预测模型：

- PRSice2
- LassoSum
- XGBoost
- Random Forest
- SVM
- MLP
- GNN
- Transformer

## 本地打开

直接用浏览器打开 `index.html` 即可，不需要安装依赖。

## 放到 GitHub Pages

1. 创建一个 GitHub repository。
2. 上传本目录中的 `index.html` 和 `README.md`。
3. 在 GitHub repository 中进入 `Settings -> Pages`。
4. Source 选择 `Deploy from a branch`，branch 选择 `main`，folder 选择 `/root`。
5. 保存后等待 GitHub Pages 生成网址。

## 答辩展示顺序建议

1. 先讲方法流程：队列与 QC、fold 内 GWAS、特征工程、模型训练、外部评估。
2. 再按左侧模型逐个点击，说明每个模型的归纳偏置。
3. 最后用对比矩阵总结：传统 PRS 是线性基线，ML 捕获非线性规则，DL 进一步学习高阶交互或样本/位点结构。
