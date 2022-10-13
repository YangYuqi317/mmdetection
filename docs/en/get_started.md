# Prerequisites

In this section we demonstrate how to prepare an environment with PyTorch.

FGVCLib works on Linux, Windows and macOS. It requires Python 3.7+, CUDA 10.0+ and PyTorch 1.5+.

```{note}
If you are experienced with PyTorch and have already installed it, just skip this part and jump to the [next section](#installation). Otherwise, you can follow these steps for the preparation.
```

**Step 0.** Download and install Anaconda from the [official website](https://www.anaconda.com/).

**Step 1.** Create a conda environment and activate it.

```shell
conda create --name openmmlab python=3.7 -y
conda activate pytorch
```

**Step 2.** Install PyTorch following [official instructions](https://pytorch.org/get-started/locally/), e.g.

On GPU platforms:

```shell
conda install pytorch torchvision -c pytorch
```

On CPU platforms:

```shell
conda install pytorch torchvision cpuonly -c pytorch
```

# Installation

We recommend that users follow our best practices to install FGVCLib However, the whole process is highly customizable. See [Customize Installation](#customize-installation) section for more information.

## Best Practices

**Step 0.** Install FGVCLib.

Please install it from source:

```shell
git clone https://github.com/dongliangchang/Fine-grained-Visual-Analysis-Library.git
```
