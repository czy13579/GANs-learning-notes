## 模型架构
CGAN 模型架构
![alt text](3cfab73a9492ff27936007f118e8b0e2.png)

CGAN 生成模型：
![alt text](50cc5362dfb925e398dc22797c644796.png)
生成器，输入的是c和z，z是随机噪声，c是条件，输出是生成的虚假图片。

CGAN 判别模型
![alt text](8753fe659af41523115055d1528b90d2.png)

## 损失函数
![alt text](v2-5f440e841389aea1496a26dee1b2a658_r.jpg)
CGAN添加的额外信息y只需要和x与z进行合并，作为G和D的输入即可，剩余步骤和一般GAN类似。



## 学习链接：
https://blog.csdn.net/weixin_40920183/article/details/118216236?ops_request_misc=&request_id=&biz_id=102&utm_term=CGAN&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-7-118216236.142^v99^pc_search_result_base9&spm=1018.2226.3001.4187

