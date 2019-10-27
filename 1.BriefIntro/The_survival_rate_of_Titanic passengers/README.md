## 简介和基础知识
## 项目：探索泰坦尼克号乘客存活情况
### 安装

本项目要求安装以下 Python 库：

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

### 代码

你可以在 notebook 文件 `titanic_survival_exploration.ipynb` 中找到代码模板。在 `visuals.py` 文件中有额外的辅助代码。我们已经提供了一些初始代码来帮助你开始，你需要补充额外函数来顺利完成本项目。请注意，学员无需更改 `visuals.py` 中的代码。如果你对 notebook 中的可视化文件感兴趣，请随意探索。


### 数据

本项目使用的数据集为 `titanic_data.csv`。该数据集由优达学城提供，并包含以下特征：

**特征**

- `Pclass`：社会阶层（1 = Upper class; 2 = Middle class; 3 = Lower class）
- `Name`：乘客姓名
- `Sex`：乘客性别
- `Age`：乘客年龄（某些条目为 `NaN`）
- `SibSp`：一起上船的兄弟姐妹和配偶人数
- `Parch`：一起上船的父母和子女人数
- `Ticket`：乘客的票号
- `Fare`：乘客支付的票价
- `Cabin`：乘客的客舱号（某些条目为 `NaN`）
- `Embarked`：乘客的登船港（C = Cherbourg; Q = Queenstown; S = Southampton）

**目标变量**
- `survival` : 存活结果 (0 = No; 1 = Yes)