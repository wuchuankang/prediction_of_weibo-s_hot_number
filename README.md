## 使用 lstm 对微热度值进行预测

数据的格式如下：  
![pic](pic/data.png)

以 like_number、comment_number、retransmit_number 在时间段上的变化率作为特征，特征还包括经过特别归一化的 hot_number，使用 LSTM 对序列进行建模，其中超参数有时间序列窗口、lstm 层数、隐变量的维度。具体的实现参见notebook 
