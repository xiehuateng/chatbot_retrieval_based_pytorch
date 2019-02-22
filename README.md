## chatbot_retrieval_based_pytorch
#### 数据
完整的数据可以在Google Drive文件夹中找到：<https://drive.google.com/open?id=1RIIbsS-vxR7Dlo2_v6FWHDFE7q1XPPgj>  
要复现文档中的代码，需要执行以下操作：  
1) 下载 以下文件:
- glove.6B.50d.txt (Subfolder GloVe)  
- training_10000.csv (Subfolder MAIN FILES)  
- validation_1000.csv (Subfolder MAIN FILES)  
- testing_same_structure_1000.csv (Subfolder MAIN FILES)  
- testing_different_structure_100.csv (Subfolder MAIN FILES)  
- saved_model_10000_gpu.pt (Subfolder SAVED MODELS)  

2) 调整变量大小 ：对于代码中出现的 num_training_examples, num_validation_examples, embedding_dim, test_dataframe_same_structure, test_dataframe_different_structure 和saved model file name 可以根据数据量的大小进行调整  

3) 调整超参数设置：具体模型的参数大家可以自己调整，也可以参考SAVED MODELS文件夹下的内容.
