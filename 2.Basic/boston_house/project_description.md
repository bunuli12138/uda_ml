# 模型评估与验证
## 项目：预测波士顿房价

## 项目概述
在此项目中，你将针对马萨诸塞州波士顿地区的房屋价格数据，应用基本机器学习概念，以预测新房屋的销售价格。首先，你将探索这些数据以获取数据集的重要特征和描述性统计信息。接下来，你要正确地将数据拆分为测试数据集和训练数据集，并确定适用于此问题的性能指标。然后，你将使用不同参数和训练集大小分析学习算法的性能图表。这能使你选择出最佳模型，来最好地泛化到未见过的数据。最后，你将根据一个新样本测试此模型并将预测的销售价格与你的统计数据进行比较。

## 项目要点
此项目旨在让你熟练地在 Python 中处理数据集，并使用 NumPy 和 Scikit-Learn 应用基本机器学习技术。在使用 sklearn 库中的许多可用算法之前，可以先练习分析和解释你的模型的性能。


通过完成此项目你将会学习以下知识：

- 如何使用 NumPy 调查数据集的潜在特征。
- 如何分析各种学习性能图以了解方差和偏差。
- 如何确定最佳猜测模型，来根据不可见数据进行预测。
- 如何评估模型使用之前的数据来处理不可见数据的性能。

## 说明
波士顿房屋市场竞争异常激烈，而你想成为当地最好的房地产中介。为了与同行竞争，你决定使用几个基本的机器学习概念，来帮助你和客户找到房屋的最佳销售价格。幸运的是，你拥有波士顿的房屋数据集，其中包含大波士顿社区房屋的各种特征的累积数据，包括其中各个地区的房屋价格的中值。你的任务是利用可用工具基于统计分析来构建一个最佳模型。然后使用该模型估算客户房屋的最佳销售价格。

## 开始项目

关于本项目，你可以在[机器学习项目 GitHub](https://github.com/udacity/machine-learning)中的 `boston_housing` 文件夹下找到项目必须的文件，在 `projects` 文件夹下。你也可以直接从这个代码库中下载本纳米学位所有项目将用到的文件。在完成任务时，请确保你使用的是项目文件的最新版本！


本项目包含三个文件：

- `boston_housing.ipynb`：这是最主要的文件，项目中的主要工作都将在这个文件上完成。
- `housing.csv`：项目数据集。你将需要把这些数据加载到 notebook 里。
- `visuals.py`：该 Python 脚本提供了项目的补充可视化文件，请勿修改。

除了项目文件外，我们还提供了 **README** 文件，其中可能包含关于项目的其他必要信息或说明。