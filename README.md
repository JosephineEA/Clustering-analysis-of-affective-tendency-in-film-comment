该项目使用斯坦福大学发布IMBD影评数据集，分析原始数据树状结构，预处理并清洗数据，使用one-hot，TF-IDF，标签编码，为树状结构数据不同级别短语分配权重的方法进行与处理。预处理后通过K-means聚类分析，并对比不同与处理方法。

1. **stanfordSentimentTreebank**：斯坦福大学发布的IMBD影评原始数据集
2. **stopwords**：从不同词库搜集来的停用词
3. **DataProcessing_for_unsupervised.ipynb**：对原始树结构数据进行预处理的代码
4. **Unsupervised.ipynb**：对预处理数据进行编码，并把不同编码后的数据使用kmeans算法进行分类的代码
5. **Make a classification of sentimental label for movie reviews.pdf**: 本项目的报告，在报告第五部分（Unsupervised Learning: K-means Clustering）对项目有详细的描述。
6. **".csv"文件**：数据预处理和模型训练过程中保存的文件


This project uses IMBD film review data set released by Stanford University to analyze the original data tree structure, preprocess and clean the data, and uses one-hot, TF-IDF, label coding to assign weights to different levels of the tree structure data. After pretreatment, K-means cluster analysis was performed, and different processing methods were compared. 
1. **stanfordSentimentTreebank**: Stanford university released IMBD reviews the original data set
2. **stopwords** : Stop words collected from different thesaurus
3. **DataProcessing_for_unsupervised.ipynb** : Code for preprocessing the original tree structure data
4. **Unsupervised.ipynb** : codes the pre-processed data and classifies the different encoded data using kmeans algorithm
5. **Make a classification of sentimental label for movie reviews.pdf**: Report of the project, in the fifth part of the report (Unsupervised Learning: K-means Clustering) has a detailed description of the project.
6. **".csv" file** : file saved during data preprocessing and model training
