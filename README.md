# pytorch-template

PyTorch 模版项目。

## 目录结构

```
pytorch-template
├── config                # 配置文件目录
├── docs                  # 说明文档目录
├── inputs                # 数据集的目录
├── models                # 网络模型目录
├── outputs               # 模型、图片文件保存目录
├── scripts               # 一些脚本文件
├── utils                 # 工具包的目录
├── .dockerignore         # Docker打包忽略文件设置
├── .editorconfig         # 文件格式编码设置
├── .gitignore            # 忽略不提交到Git的文件
├── export.py             # 模型导出脚本
├── README.md             # 项目介绍文档
├── requirements.txt      # 项目依赖库配置
├── train.py              # 模型训练脚本
└── val.py                # 模型验证脚本
```

## 环境配置

```
# 创建虚拟环境
conda create -n my_venv python=3.8

# 启用虚拟环境
conda activate my_venv

# 安装依赖库
pip install -r requirements.txt

# 或者指定镜像源
pip install -r requirements.txt -i https://mirror.baidu.com/pypi/simple
```
