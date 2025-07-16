### Purified Contrastive Learning with Global and Local Representation for Hyperspectral Image Classification

<font color='#88CDF6'>Lin Zhao; Jia Li; Wenqiang Luo; Er Ouyang; Jianhui Wu; Guoyun Zhang; Wujin Li</font>

<hr>
The code in this toolbox implements the

["Purified Contrastive Learning With Global and Local Representation for Hyperspectral Image Classification"].(https://ieeexplore.ieee.org/document/10547362)

More specifically, it is detailed as follow.

![](Framework.png)

Four kinds of HSI transformation operations are detailed as follow:

![](operations.png)


### System-Spefic notes:

The experimental computer setup includes an Intel(R)
Core(TM) i7-10700F processor, an NVIDIA GeForce RTX 2060 SUPER graphics card, and Python version 3.8.5 and PyTorch version 1.7.1 as the programming language and deep
learning platform, respectively.

<hr>

### How to use it?
First, running the `pretrain_main.py` to pretrain the model, This operation will get a weight folder. Running the `finetune.py` then, you will achieve the final results.


<hr>

### Citation
**Please kindly cite the papers if this code is useful and helpful for your research.**
```
@ARTICLE{9734031,
  author={Zhao, Lin and Luo, Wenqiang and Liao, Qiming and Chen, Siyuan and Wu, Jianhui},
  journal={IEEE Geoscience and Remote Sensing Letters}, 
  title={Hyperspectral Image Classification With Contrastive Self-Supervised Learning Under Limited Labeled Samples}, 
  year={2022},
  volume={19},
  number={},
  pages={1-5},
  keywords={Feature extraction;Task analysis;Supervised learning;Hyperspectral imaging;Jitter;Training;Kernel;Contrastive learning;hyperspectral image (HSI) classification;limited labeled samples;self-supervised learning~(SSL)},
  doi={10.1109/LGRS.2022.3159549}}
```
<hr>

### Licensing
Copyright (C) 2022 Lin Zhao

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with this program.







