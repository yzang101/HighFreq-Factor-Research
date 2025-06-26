# 高频动量因子构建与验证项目

本项目是我的一个练习项目\
旨在基于高频数据构建股票动量类因子，并通过多因子合成、建模与策略回测，对五只美国股票进行系统性分析与实证研究。

## 📁 项目结构

```
五个股票高频动量因子构建及验证/
├── resample_output/          
├── notebook/     
├── output/
├── strategy_results/      
├── README.md       # 项目说明文件
├── requirements.txt # 项目依赖
└── .gitignore       # Git 忽略文件配置
```



## 📈 项目目标

- 构造高频动量相关特征（momentum、bias、volatility 等）
- 合成 alpha signal（线性加权 & ML 打分）
- 使用 Lasso 与 Logistic Regression 进行因子筛选
- 对策略进行回测并与 Buy & Hold 策略对比
- 输出 IC 值、分组分析图、资金曲线等指标

## 🛠️ 使用技术

- Python（Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Scipy）
- Jupyter Notebook
- Git & GitHub
- 高频分钟级数据（1min / 5min / 60min）

## 📊 样例结果

- **累计收益对比图（Cumulative Return）**
- **因子 IC 排名**
- **Lasso/LR 系数分析**
- **分组收益柱状图**

是我第一次想要尝试独立完成这样一个项目，有很多不足，如果有发现问题，欢迎指出
