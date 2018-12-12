# Mixed-Senet-Densenet
In this repository, I released senet-densenet training codes and output files. And it refer to another [repository](https://github.com/zhouyuangan/SE_DenseNet), which repository I had made some notes in. [Chinese version blog](https://zhuanlan.zhihu.com/p/48499356), [English version blog](http://www.zhouyuangan.cn/2018/11/se_densenet-modify-densenet-with-champion-network-of-the-2017-classification-task-named-squeeze-and-excitation-network/)

## Experiments

In another repository, I had made some annotations about different structures of senet-densent, pls check [here](https://github.com/zhouyuangan/SE_DenseNet) for more details, and there are some charts and datas visualized by matplotlib too.

## Usages:

### Download dataset

Cifar10 dataset is easy to access it's website and download it into `data/cifar10`, you can refer to pytorch official tutorials about how to train on cifar10 dataset.

### Training

There are some modules in `core` folder, before you start training, you need to edit code in `cifar10.py` file to change `from core.se_densenet_xxxx import se_densenet121`,

Then, open your terminal, type:
```bash
python cifar10.py
```

## Visualize training

In your terminal, type:
```bash
python visual/viz.py
```
Note: please change your state file path in /visual/viz.py.

Refer:

[another repo of senet-densenet](https://github.com/zhouyuangan/SE_DenseNet)

[Chinese version blog](https://zhuanlan.zhihu.com/p/48499356)

[English version blog](http://www.zhouyuangan.cn/2018/11/se_densenet-modify-densenet-with-champion-network-of-the-2017-classification-task-named-squeeze-and-excitation-network/)