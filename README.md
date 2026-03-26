# 基于单细胞转录组数据的肺腺癌转移代谢驱动因子鉴定与靶向药物筛选研究

## 📖 项目简介 (Introduction)
本项目为 《基于单细胞转录组数据的肺腺癌转移代谢驱动因子鉴定与靶向药物筛选研究》的配套数据。

研究利用scRNA-seq技术探索LUAD转移过程中的代谢重构机制。通过鉴定关键代谢驱动基因（MDGs），构建预后风险评分模型，并结合 DrugBank 数据库进行靶向药物预测，旨在为肺腺癌转移的精准治疗提供新的科学依据。

## 📂 目录结构 (Project Structure)
```text
├── data/                 # 数据存放目录（包括处理后的精简表达矩阵）
├── results/              # 关键分析结果表格
│   ├── DEGs_list.csv     # 差异表达基因列表
│   ├── MDGs_14.csv       # 最终纳入模型的14个核心代谢驱动基因
│   ├── NMF_Clusters.csv  # NMF 亚型分类结果 (C1/C2/C3)
│   └── Drug_Screen.csv   # 潜在靶向药物列表
├── scripts/              # 核心分析脚本 (R Language)
└── README.md             # 项目说明文档
