# 安装SyntaxNet
有了tensorflow，我们可以开始安装syntaxnet. 在这个github repository的guide文件夹中，我们仅从
如何安装相关环境，安装syntaxnet, 用预先训练的官方初级模型提取英文语义，并简要介绍如何利用
官方预先初步训练的中文模型提取中文语义。目前我们已经可以用自己感兴趣的内容训练独具功能的
中文语义分析模型。但关于用特定语料库训练中文模型，我们暂不在这里讨论。
（官方介绍 https://github.com/tensorflow/models/tree/master/syntaxnet）</br>

下面我们开始。
### 为安装syntaxnet做准备：
#### 安装Bazel

在某种情况下面，Bazel无法安装上去，一直提示要安装:  
```
dpkg: error processing archive /var/cache/apt/archives/openjdk-9-jdk_9~b114-0ubuntu1_i386.deb (--unpack):
```

可以采用以下解法：
```
sudo apt-get -o Dpkg::Options::="--force-overwrite" install openjdk-9-jdk
```
