# Stock-analysis-Named-Entity-Recognition
## 本项目主要面向产品竞争类分析中股权关系数据进行分析，本实验通过Bert-BiLSTM-CRF方法进行命名实体识别，本次实验主要识别买方（Buyer）、卖方（Seller）、标的（Target）三种实体。
**编写人：卢克治<br>时间：2020年8月24日<br>项目功能：面向股权关系数据通过Bert-BiLSTM-CRF模型进行命名实体识别<br>**
- The named entity recognition function of stock relationship data, which identify three types of entities: buyer, seller and target.<br>
+ 本模型细节和代码主要参考使用：[BERT-BiLSTM-CRF-NER](https://github.com/macanv/BERT-BiLSTM-CRF-NER)<br>
* 本模型使用的Bert模型主要下载以下资源中的RoBERTa-wwm-ext-large, Chinese模型：[中文Bert模型汇总](https://github.com/ymcui/Chinese-BERT-wwm)<br>

---
## 1：数据清洗：
+ 数据清洗功能主要完成对股权关系已标注好的数据进行BIO方式文件的转化。转化好的BIO文件可以作为以下Bert-BiLSTM-CRF进行命名实体识别的模型输入。
+ 输入数据在：[数据清洗/inputData](https://github.com/lgxt/Stock-analysis-Named-Entity-Recognition/tree/master/%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97/inputData)目录下；
+ 输出数据在：[数据清洗/outputData](https://github.com/lgxt/Stock-analysis-Named-Entity-Recognition/tree/master/%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97/outputData)目录下；
+ 脚本运行为：[数据清洗/NER-dataset-按每条公告汇总标注构建数据集-统一公告id.py](https://github.com/lgxt/Stock-analysis-Named-Entity-Recognition/blob/master/%E6%95%B0%E6%8D%AE%E6%B8%85%E6%B4%97/NER-dataset-%E6%8C%89%E6%AF%8F%E6%9D%A1%E5%85%AC%E5%91%8A%E6%B1%87%E6%80%BB%E6%A0%87%E6%B3%A8%E6%9E%84%E5%BB%BA%E6%95%B0%E6%8D%AE%E9%9B%86-%E7%BB%9F%E4%B8%80%E5%85%AC%E5%91%8Aid.py)<br>
"```
python NER-dataset-按每条公告汇总标注构建数据集-统一公告id.py
```"

### 1.1：输入数据：
### 1.2：输出数据：

_ _ _
## 2：模型训练：
### 2.1：Docker镜像的使用：
### 2.2：使用Docker镜像使用gpu进行模型训练：

_ _ _
## 3：模型预测：

