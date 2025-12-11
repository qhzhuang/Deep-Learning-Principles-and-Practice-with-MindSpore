## 深度学习原理与MindSpore快速入门

介绍深度学习的核心概念与原理, 通过MindSpore的API来快速实现一个简单的深度学习模型。

### 实验链接

- [官网链接](https://www.mindspore.cn/tutorials/zh-CN/r2.7.1/beginner/quick_start.html)

- [代码仓链接](https://gitee.com/mindspore/docs/blob/r2.7.1/tutorials/source_zh_cn/beginner/quick_start.ipynb)

### 注意事项

该实验可在硬件Ascend和CPU上执行，安装教程请参考[MindSpore快速安装](https://www.mindspore.cn/install)，安装时注意区分Ascend和CPU。在运行之前注意检查MindSpore是否安装成功。

- Ascend硬件

执行以下命令

```bash

python -c "import mindspore;mindspore.set_device('Ascend');mindspore.run_check()"

```
如果输出

```text

MindSpore version: 版本号
The result of multiplication calculation is correct, MindSpore has been installed on platform [Ascend] successfully!

```
说明MindSpore安装成功。

- CPU硬件

执行以下命令

```bash

python -c "import mindspore;mindspore.set_device('CPU');mindspore.run_check()"

```
如果输出

```text

MindSpore version: 版本号
The result of multiplication calculation is correct, MindSpore has been installed on platform [CPU] successfully!

```
说明MindSpore安装成功。
