# 从零构建AI推理引擎系列

**引言**: 现在有很多开源推理引擎，也有很多同学做模型部署相关工作，但大部分仅仅停留在“用工具”的层面。假如你想掌握技术的本源，停留在用工具层面是远远不够的。

我将最近业余玩耍的自建AI推理引擎相关博客文章整理成一个索引，里面记录了一些我在建造过程中踩过的坑，以及一些关于 **C++语言、框架架构、算子推理设计、用户体验设计** 的一些实践和思考，希望对大家有用。

AI已经到了一个非常成熟的阶段，我们要做的，不仅仅是 `python train.py`，我们要做的是更进一步的将AI推延到工业领域，而这离不开一个好用的推理引擎。但仅停留在用开源的工具未免有些浅显，比如 有社区同学就问我MNN编译的库体积较大如何解决？有人问题我为什么某些框架的layernorm很慢等等，如果你深入知道它背后的实现原理，这些问题自然就知道答案了。

这个仓库持续更新中，如果你对 AI部署落地，AI算法应用感兴趣，可以搜索微信公众号关注一波： `神力人工智能` 。不定期分享一些技术干货。


## 动态

本系列一直在更新中，一直没有停更，简单动态记录：

**`2022.09.08`** : 忙于模型优化，暂时停了一段时间，下次将使wnnx能够推理自研的YOLO系列目标检测模型；


## 索引


### 1. 基础进阶

- 为什么要构建推理引擎
- 推理框架实现123
- [WNNX从0实现AI推理引擎（一）](https://www.yuque.com/docs/share/39b4cdc7-3379-4cf1-86a5-3a261fcde5f1)
- [WNNX从0实现AI推理引擎（二）](https://www.yuque.com/docs/share/d164b0cd-8dc9-41e9-a1ad-e0e83af72152)
- [WNNX从0实现AI推理引擎（三）](https://www.yuque.com/docs/share/94e5a932-25ed-4b52-9c7a-0cd928c6500a)
- [WNNX从0实现AI推理引擎（四）](https://www.yuque.com/docs/share/5c19f243-aac3-4a4a-baa8-a8c6730b4cf1)
- [WNNX从0实现AI推理引擎（五）](mds/2022_06_06_12_WNNX从0实现AI推理引擎（五）.md)
- [WNNX从0实现AI推理引擎（六）](mds/2022_06_07_11_WNNX从零实现一个AI推理引擎（六）.md)
- [WNNX从0实现AI推理引擎（七）](mds/2022_08_01_03_WNNX从0实现AI推理引擎之终结篇前序.md)
- [WNNX从0实现AI推理引擎（八）](mds/2022_06_06_12_WNNX从0实现AI推理引擎（五）.md)
- [WNNX从0实现AI推理引擎（九）](mds/2022_06_06_12_WNNX从0实现AI推理引擎（五）.md)


### 2. 花式玩法

- [将引擎链接到TensorRT]()
- [自建引擎推理YOLOX]()
- [自建引擎推理BERT]()
- [自建引擎推理语音识别模型]()
- [自建引擎推理语音合成模型]()


### 3. 骨灰级

- [自建引擎如何编译一个exe进行AI模型分发]()
- [如何移花接木将其他的引擎的东西融合进入自建引擎]()
- [用自建引擎建造一个自动表白机器人送给女朋友]()
- [自建引擎从入门到入土]()


### 4. 外延（产品经理用)

- [如何给框架设计进行用户体验设计？]()
- [真正的软件如何做到用户友好]()
- [用户用你的SDK到底是在用什么？]()
- [自建推理引擎如何商业化（工业化）落地]()


## 版权

All rights reserved by Lucas Jin @ 2022. 
