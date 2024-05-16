# Python in Omics
### 环境准备
Python最常用的IDE（编辑器）为VS code，这个编辑器可以兼容绝大多数主流编程语言，并且有较多的插件。[VS Code下载]（https://visualstudio.microsoft.com/zh-hans/downloads/）
此外，对于数据分析和可视化，Jupyter Notebook因为便于阅读与分享，也是一个流行的选择。[Anaconda & Jupyter Notebook的下载与使用](https://zhuanlan.zhihu.com/p/228114733)

## Tasks
### 文件描述
HMDB和ChEBI是两个代谢物小分子数据库，分别储存在了chebi.csv和hmdb.csv当中，对于每个代谢物包含Accession（代谢物的ID），Name（代谢物的名字），Monoisotopic Mass（代谢物的质量），InChIKey和SMILES（两个代谢物的表示符号）。
### Task 1 dataframe的处理
Pandas（[教程](https://www.runoob.com/pandas/pandas-tutorial.html)）是Python中最流行的数据处理package，在这个task中将使用这个package完成对表格的数据处理与输出。
* **下载pandas，并读取两个表格，作为dataframe**
* 通常代谢物被认为是质量（Monoisotopic Mass）小于等于1500 Da的小分子，**对于两个数据集，仅保留Monoisotopic Mass这一列的值小于1500的行**
* [InChI Key](https://www.inchi-trust.org)是一种化学表示符号，其中，包含3个layers，通过‘-’分隔开来，其中第一个layer包含了主要的化学信息，添加一个新的列（InChIKey_main）,

### Task 2 可视化
### Task 3 搜索与输出
### Task 4 基础算法的实施

### 其他参考材料
