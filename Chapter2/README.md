## minGPT开发训练推理全流程实践

本节以minGPT项目为例, 介绍Transformer网络的结构、混合精度训练、语言模型解码原理。

### 课程材料

- [代码](https://github.com/mindspore-lab/orange-pi-mindspore/tree/dev/courses/02_mingpt)
- [PPT](./minGPT训推.pptx)
- [视频](https://www.hiascend.com/developer/courses/detail/1925362775376744449)(第6-10章)


### 注意事项

该案例可在香橙派开发板与910B上运行

- 如果在香橙派开发板上运行, 请按照开发板代码仓的[环境搭建](https://github.com/mindspore-lab/orange-pi-mindspore/tree/dev/courses/02_mingpt)搭建好环境后再运行案例。

- 如果在910B上运行, 环境搭建可参考[Dockerfiles](https://github.com/mindspore-lab/step_into_llm/tree/dev/03.MindSpore_Compatible_Training_Course/dockerfiles), 或使用华为云[ModelArts](https://console.huaweicloud.com/modelarts/?region=cn-southwest-2#/dev-container/create)上的环境。