# 17-分来分去-焦子逊-李劲草-何苗-西安工程大学

## test
python test.py --mode validation

* 测试数据集路径在test.py中 --data_path 可改
* --mode validation 与 测试文件夹名称一致
* 保存路径在 --dump_path
* 权重文件放在 ./checkpoints中 分别对应 --pretrained 和 --centroid
* 结果保存在 ./result/validation 中

## train
bash train.sh

* 训练数据集路径在sh文件可改

## 结果
19.7203