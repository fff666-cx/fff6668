# 任务一 3DDFA_V2复现

唇语识别中经常遇到说话人头部姿态晃动的问题，考虑使用人脸配准方法对人脸进行矫正。

### 任务要求

1. 根据原始[代码库](https://github.com/cleardusk/3DDFA_V2)，复现3DDFA_V2

2. 使用代码库提供的预训练权重，在LRS2上检测人脸，选择10个样例提供2D sparse的可视化结果

   > [!NOTE]
   >
   > 数据集根据3DDFA_V2的输入要求进行处理

   ![2d sparse](https://github.com/cleardusk/3DDFA_V2/raw/master/docs/images/trump_hillary_2d_sparse.jpg)

3. 参考 [retinaface](https://github.com/serengil/retinaface/tree/master)中[postprocess](https://github.com/serengil/retinaface/blob/master/retinaface/commons/postprocess.py)提供的`alignment_procedure`，对齐人脸，同样提供10个样例的结果

![img](https://raw.githubusercontent.com/serengil/retinaface/master/tests/outputs/alignment-procedure.png)