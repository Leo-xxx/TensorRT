## 英伟达深度学习推理引擎TensorRT，现在开源了

[机器之心](javascript:void(0);) *今天*

机器之心报道

**参与：李亚洲、李泽南、思**

> 英伟达的深度学习推理引擎TensorRT是连接神经网络框架与GPU之间的桥梁，它支持所有种类的神经网络框架，近期也实现了容器化，目前的TensorRT是5.1版。6月17日，英伟达宣布了TensorRT的开源。

项目链接：https://github.com/NVIDIA/TensorRT



本次开源的内容是英伟达 TensorRT 的一部分，其中包括 TensorRT 的插件与一些解析器（Caffe 和 ONNX），以及演示 TensorRT 平台的使用和功能的示例应用程序。相信未来更多的内容也会持续开源。



![img](https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW8hJtUXYtBibtqPoVfrSJ8TphZrswp6RsbX6ZnQC3d49ibSmKjHZoTNXA9ApEn0fxx2b6MW6H5M3H1g/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)



TensorRT 是一个高性能[深度学习](https://mp.weixin.qq.com/s?__biz=MzA3MzI4MjgzMw==&mid=2650764251&idx=4&sn=5a06837815d0ad9e381275d6e9942f7d&chksm=871ab7a5b06d3eb3166f0cbd32408b955e3fe61c743397c48fd99af305e2b882e2ddf92c23f2&mpshare=1&scene=1&srcid=&key=f750944ce987c74946c57a4c0039cf5c203857c8f433502a72e4c3de5a4285ce9e90ad1890c6218521137725ed2be12665dad8bf3f9ac7296f7553dbbfd11f8967072906ba49788de69041d782c22e2a&ascene=1&uin=MjMzNDA2ODYyNQ%3D%3D&devicetype=Windows+10&version=62060833&lang=zh_CN&pass_ticket=IHr7aSrMWFAJvtZIOmsKdFXjgAgb6nM0lYokd2Lk8wBQmZtPkRq58oNxSL2Vg8Lf)推理平台，能够为在英伟达 GPU 上运行的语音、视频等 APP 提供更低地延迟、更高的吞吐量。TensorRT 包含输入模型的解析器、支持全新 ops 的插件以及在利用优化进行推理之前的层。



今日，英伟达宣布开源 TensorRT 中的解析器和插件部分，以便于深度学习社区能够做自定义、扩展组件，从而更好的利用 TensorRT 进行 app 优化。



TensorRT 的 GitHub 项目目前已经开放了，其包括贡献指南，它会告诉我们如何参与这一优秀工具的完善。英伟达表示他们将在新版本发布时，合并且发布最新的代码。



例如你可以贡献：



- 针对 ONNX 格式和 Caffe 扩展解析器，用全新 ops 把模型输入到 TensorRT
- 插件程序让你能够在 TensorRT 中运行自定义 ops。使用开源的插件作为参考，或者建立全新的插件从而支持新的层（layers）
- 示例只是提供了一个起点，用户也可以贡献全新工作流和管道的示例。



英伟达的目标在于为社区提供更多的特性，并同时更方便地利于开发者对社区做出贡献。英伟达开发者博客介绍了如何开始使用 TensorRT，读者们也能从 TensorRT 的产品页面或这次新构建的 GitHub 项目获取它。



官方教程：如何使用 TensorRT 加速深度学习推断

地址：https://devblogs.nvidia.com/speed-up-inference-tensorrt/



最后，GitHub 项目中对于如何安装 TensorRT 开源软件及构建环境都有非常详细的描述，感兴趣的读者快来试试吧。*![img](https://mmbiz.qpic.cn/mmbiz_png/KmXPKA19gW8Zfpicd40EribGuaFicDBCRH6IOu1Rnc4T3W3J1wE0j6kQ6GorRSgicib0fmNrj3yzlokup2jia9Z0YVeA/640?wx_fmt=png&tp=webp&wxfrom=5&wx_lazy=1&wx_co=1)*



*参考内容：*

*https://news.developer.nvidia.com/nvidia-open-sources-parsers-and-plugins-in-tensorrt/https://github.com/NVIDIA/TensorRT*





**本文为机器之心报道，转载请联系本公众号获得授权。**

✄------------------------------------------------

**加入机器之心（全职记者 / 实习生）：hr@jiqizhixin.com**

**投稿或寻求报道：content@jiqizhixin.com**

**广告 & 商务合作：bd@jiqizhixin.com**









微信扫一扫
关注该公众号