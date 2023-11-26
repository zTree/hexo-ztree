---
title: TensorFlow 之 手写数字识别 01
index_img: /img/pages/DigitRecognition.jpeg
tags: [AI, TensorFlow, 深度学习]
categories:
- [学习, TensorFlow]
--- 

![来自：Bing 的 AI 创建（ Prompt： 手写数字识别 ）](/img/pages/DigitRecognition.jpeg)

## 手写数字识别 扩展01

一个月前用了官方提供的demo，实现了手写数字识别的训练，最近终于抽空加上了手写的交互，用户可以在 demo中自己手写数字，查看识别的结果。

你可以在训练前先做几个识别测试，会发现测试结果很糟糕， 开启训练后，再来手写输入，你会发现识别结果好很多，但距离理想还有一定距离，估计是用来训练的数据量不够， 7 和 9 我自己手写的识别度一直都很差。 后面看，能否把自己的手写结果加进去，同时把训练结果尝试保存在浏览器里，再就是看看能否依靠调节深度学习的一些层数和算法来提升识别度。

有兴趣的可以来尝试一下：
Demo：[https://treejs.cn/tensorflow](https://treejs.cn/tensorflow) 



