# Machine Learning Algorithms

这是一个机器学习算法的 Jupyter Notebooks 合集，涵盖了分类、聚类、回归等多种机器学习算法的实现与应用。

## 项目结构

```
algorithms/
├── data/                           # 数据集目录
│   ├── breast-cancer-wisconsin.csv # 乳腺癌数据集
│   ├── customers.csv               # 客户数据集
│   └── titanic.csv                 # 泰坦尼克号数据集
├── FBlocation/                     # Facebook 位置数据
│   ├── train.csv                   # 训练数据
│   └── test.csv                    # 测试数据
├── classification_news.ipynb       # 新闻分类
├── cluster.ipynb                   # 聚类算法
├── decision_trees.ipynb            # 决策树
├── KNN_facebook.ipynb              # KNN算法 - Facebook位置预测
├── KNN_Facebook_1.ipynb            # KNN算法 - 改进版
├── KNN_facebook_enhanced.ipynb     # KNN算法 - 增强版
├── lasso_ling.ipynb                # Lasso回归
├── logic_regression.ipynb          # 逻辑回归
├── naive_bayes.ipynb               # 朴素贝叶斯
└── random_trees.ipynb              # 随机森林
```

## 算法列表

### 分类算法

| Notebook | 算法 | 应用场景 |
|----------|------|----------|
| `naive_bayes.ipynb` | 朴素贝叶斯 | 文本分类、垃圾邮件检测 |
| `logic_regression.ipynb` | 逻辑回归 | 二分类问题 |
| `decision_trees.ipynb` | 决策树 | 分类与回归 |
| `random_trees.ipynb` | 随机森林 | 集成学习、特征重要性分析 |
| `classification_news.ipynb` | 多分类器 | 新闻主题分类 |

### 聚类算法

| Notebook | 算法 | 应用场景 |
|----------|------|----------|
| `cluster.ipynb` | K-Means | 数据分群、模式发现 |

### KNN 系列

| Notebook | 描述 |
|----------|------|
| `KNN_facebook.ipynb` | K近邻算法基础实现 |
| `KNN_Facebook_1.ipynb` | 改进版本 |
| `KNN_facebook_enhanced.ipynb` | 增强版本 |

### 回归算法

| Notebook | 算法 | 应用场景 |
|----------|------|----------|
| `lasso_ling.ipynb` | Lasso回归 / 岭回归 | 特征选择、稀疏建模 |

## 环境要求

- Python 3.8+
- Jupyter Notebook / JupyterLab

### 核心依赖

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

## 快速开始

### 1. 克隆仓库

```bash
git clone https://github.com/justsosoli/python_ai.git
cd python_ai
```

### 2. 安装依赖

```bash
pip install numpy pandas scikit-learn matplotlib seaborn jupyter
```

### 3. 启动 Jupyter

```bash
jupyter notebook
```

## 数据集说明

| 数据集 | 描述 | 用途 |
|--------|------|------|
| breast-cancer-wisconsin | 乳腺癌诊断数据集 | 二分类 |
| customers | 客户数据 | 客户分群 |
| titanic | 泰坦尼克号乘客生存数据 | 生存预测 |
| FBlocation | Facebook 位置签到数据 | 位置预测 |
