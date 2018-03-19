# IJCAI 2018 阿里妈妈国际广告算法大赛 baseline

当前使用训练集合中最后一天的数据作为验证集，logloss为0.0818，线上成绩为0.0831。

# 使用说明

1. 将解压后的数据文件放在代码同级目录下，包括`round1_ijcai_18_train_20180301.txt`和`round1_ijcai_18_test_a_20180301.txt`
2. 修改代码`第30行`处的标记来区分线下验证和在线提交

# 特征说明

除了基本特征外，还包括了**用户在当前小时内和当天的点击量统计特征**，以及**当前所在的小时**。

# 其他参考资料
1. [腾讯社交广告高校算法大赛 移动App转化率预估 竞赛方案](https://github.com/shenweichen/Tencent_Social_Ads2017_Mobile_App_pCVR)
2. [基于深度学习的CTR预估模型](https://github.com/shenweichen/DeepCTR) 
