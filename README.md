# 由来

开发过程中，我们经常会遇到**产品**、**测试**以及**高管**拿着当前项目和市面上类似功能的app进行对比，他们会提出一些体验过程中觉得不足的地方，其中功能性的问题和我们关系不大，主要是**产品**需要考虑的问题，但是一些体验方面的差距就需要我们去发现问题并解决问题。

我们拿到这些反馈可能会觉得无从下手。我们确实是按照正确的方法实现了产品给定的需求，但是为什么会产生截然不同两种的体验效果呢？我们该怎么发现是什么导致这些体验差距，又是该怎么提升体验呢？

这里针对`可乐优品`[^1]和`找靓机`[^2]两个进行app性能分析[^3]对比，并对后续`可乐优品`的优化提出初步的解决方案。



[^1]: 公司的主打产品，用来提供给用户回收旧机以及购买新机，体验[链接](http://www.keleyoupin.com.cn/)。

[^2]: 京东旗下的二手电子产品回收APP，体验[链接](https://m.aihuishou.com/n/#/?bd_vid=7847937322261861363&type=0)。

[^3]: 市面上存在很多的性能分析工具，这里不对他们进行一一介绍，本文展示的数据来自[Android Studio](https://juejin.im/post/5a351a76f265da430d58165a)和[PerfDog](https://bbs.perfdog.qq.com/article-detail.html?id=5)。
