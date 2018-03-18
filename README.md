# IJCAI 2018 阿里妈妈国际广告算法大赛

# 使用说明

1. 将解压后的数据文件放在代码同级目录下，包括`round1_ijcai_18_train_20180301.txt`和`round1_ijcai_18_test_a_20180301.txt`
2. 修改代码`第22行`处的标记来区分线下验证和在线提交

# 特征说明

除了基本特征外，还包括了**用户在当前小时内和当天的点击量统计特征**，以及**当前所在的小时**。

# 模型

使用了[LightGBM](https://github.com/Microsoft/LightGBM)