项目名称 jittor-【我该怎么应对】-【jittor热身赛】

简介
该项目为利用cgan模型生成特定数字的图片

安装
本项目使用CPU|(amd r5 6600h)运行，运行时间在5-6个小时之间

运行环境
ubuntu 20.04 LTS
python >= 3.7
jittor >= 1.3.0
安装依赖
执行以下命令安装 python 依赖

pip install -r requirements.txt
训练
单卡训练可运行以下命令：

python CGAN.py
推理
可通过调用如下代码生成指定数字字符的手写数字照片
number = “要生成的数字序列”
