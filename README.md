# Classification Project based on Pytorch
这是一份基于Pytorch的分类代码，用于deep-learning、Pytorch的学习。
#### 相关信息
    开始日期：2019.6.9
#### 环境要求
    Pytorch1.0+
    tensorboardX
    yaml
    easydict
    Some other libraries (find what you miss when running the code. hhhhh~)
#### 实现模型
    LeNet
    AlexNet
    ResNet
#### 数据准备
    1.cifar10:
    直接运行训练代码即可，可以自行下载解压；
    2.easy:
    https://pan.baidu.com/s/1rzKT6VvmSmoHEKdPmLMc6Q 提取码cx9a.选择第二题的分类数据集，
    在该数据集下新建tranval和test文件夹用于存放训练与测试集；
#### 预训练模型
    需要的预训练模型会自动下载在.cache/torch下；
#### 使用方法
    实验名在exp_configs文件夹下以文件夹名体现；
    模型输出在exp_output，在classification_Tensorflow_Proj路径下新建一个exp_output，
    内新建对应的实验名文件夹;
    运行方法是先在exp_configs里做好实验配置，再运行指定好的train.py文件。
    