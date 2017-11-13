# TensorFlow

一步一步记录下学习TensorFlow的过程。
ref:
  - 简书：[不会停的蜗牛](http://www.jianshu.com/p/6766fbcd43b9)

## Installation

- [极客学院中文版安装教程](http://wiki.jikexueyuan.com/project/tensorflow-zh/get_started/os_setup.html)
- [Github上的安装教程](https://github.com/tensorflow/tensorflow#installation)

### Python安装

### Pip安装

### 使用virtualenv

### TensorFlow安装
- 建立一个tensorflow的独立环境: `virtualenv --system-site-package tensorflow && cd tensorflow`
- 激活环境：`source bin/active`；成功激活环境之后终端提示符会发生改变：`(tensorflow) ➜  tensorflow`
- 在新的环境内安装TensorFlow(可能需要科学上网，失败几次之后我才成功安装)：
  - `pip install --upgrade https://storage.googleapis.com/tensorflow/mac/tensorflow-0.8.0rc0-py2-none-any.whl`
- 进入终端测试：
```
$ python
>>> import tensorflow as tf
>>> session = tf.Session()
>>> a = tf.constant(1)
>>> b = tf.constant(2)
>>> print(session.run(a + b))
3
>>>
```
- 成功输出则安装成功。
- 退出环境：`deactive`。再次使用的时候重新激活即可。
