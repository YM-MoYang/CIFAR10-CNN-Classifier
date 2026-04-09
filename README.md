# CIFAR10 CNN 图像分类器
基于卷积神经网络的 CIFAR10 图像分类项目，包含多个预训练模型。

## 项目说明
使用 PyTorch 实现的 CNN 模型，对 CIFAR10 数据集的10个类别进行图像分类。

## 包含的模型文件
- `cifar_net.pth` - 基础CNN模型
- `MyNet_base.pth` - 基础网络
- `MyNet_medium.pth` - 中等网络
- `MyNet_large.pth` - 大型网络（效果最好）

## 如何使用

### 1. 安装依赖
```bash
pip install -r requirements.txt
```

### 2. 运行程序
- 启动 Jupyter Notebook，打开 Main.ipynb 运行即可
### 3. 数据集
  首次运行时会自动下载 CIFAR10 数据集（约163MB）

## 环境要求

- Python 3.8+
- PyTorch 1.9+
- Jupyter Notebook

## 项目结构

- ├── Main.ipynb           主程序
- ├── *.pth                预训练模型（4个）
- ├── requirements.txt     依赖包列表
- └── .gitignore           Git忽略配置

## 注意事项

- 通过torchvision库对数据集进行下载，如果在国内则需要VPN
- 尽量使用GPU运行，CPU速度较慢
