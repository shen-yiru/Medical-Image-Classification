medical-image-classification/
├── .gitignore          # Git忽略文件
├── LICENSE             # 许可证
├── README.md           # 项目说明
├── requirements.txt    # Python依赖
├── data/               # 数据集
│   ├── raw/           # 原始数据
│   ├── processed/     # 处理后的数据
│   └── README.md      # 数据说明
├── notebooks/          # Jupyter笔记本
│   ├── 01_data_exploration.ipynb
│   ├── 02_model_training.ipynb
│   └── 03_evaluation.ipynb
├── src/                # 源代码
│   ├── __init__.py
│   ├── data_loader.py  # 数据加载
│   ├── models.py       # 模型定义
│   ├── train.py        # 训练脚本
│   └── utils.py        # 工具函数
├── models/             # 训练好的模型
│   └── README.md
├── tests/              # 测试代码
│   └── test_models.py
├── docs/               # 文档
│   ├── api.md         # API文档
│   └── tutorial.md    # 教程
└── scripts/            # 脚本文件
    ├── setup.sh       # 环境设置
    └── train.sh       # 训练脚本


# Medical-Image-Classification
基于深度学习的医学影像分类系统
技术栈：PyTorch + OpenCV + Flask
数据：公开数据集（COVID-CT, CheXpert）
功能：数据预处理、模型训练、Web演示
亮点：结合医学影像研究兴趣
