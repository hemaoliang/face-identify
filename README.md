# face-identify
使用CNN网络类型中的VGG网络结构，训练人脸分类模型，提取人脸特征

-------------------------------------------------------------------------------
1、使用的数据集为2622个电影明星的包含人脸的图片，每个个体包含1000张图片（数据质量比LFW数据集要好，个体样本充足）
2、使用dlib或者opencv检测图片中的人脸
3、使用dlib的人脸基准点检测方法，把人脸数据对齐标准化
4、使用vgg模型训练人脸分类，最层的full-connect-layer作为提取的人脸特征

参考资料
[1] http://www.robots.ox.ac.uk/~vgg/data/vgg_face/ (VGG-Face CNN 中采用的人脸数据集，2622乘1000张图片)
[2] http://www.robots.ox.ac.uk/~vgg/software/vgg_face/ (VGG-Face CNN 相关的source code) 
[3] http://cmusatyalab.github.io/openface/ (开源的人脸识别项目 openface)
[4] https://github.com/cmusatyalab/openface (openface的source code)
