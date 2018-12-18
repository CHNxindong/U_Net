# U_Net
unet pytorch

pytorch: 0.40 
python : 3.5

复现unet，发现pytorch对于这种用到中间层的，写的代码要麻烦一点，需要设置输入通道，特别注意forward。在这里不如keras tensorflow/slim 自动获取输入通道要方便一些。

但是，pytorch在好多方面要好用许多，有更规范的格式。tf太臃肿了。。。

pytorch还缺少对tensor的旋转/翻转等类似tensorflow的tf.image的库函数。期待1.0

