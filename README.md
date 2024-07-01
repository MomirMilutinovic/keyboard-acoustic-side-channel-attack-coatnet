# keyboard-acoustic-side-channel-attack-coatnet
This is an implementation of the paper [A Practical Deep Learning-Based Acoustic Side
Channel Attack on Keyboards](https://arxiv.org/pdf/2308.01074).

`keyboard-side-channel.ipynb` contains the training run, and is the main file of the implmentation of the model used in the paper. However, the actual test results are in `keyboard-side-channel-classification-report` as the former file reports test results of the last epoch instead of the epoch in which the best validation accuracy was reached.

# Acknowledgments
I have found these resources useful while writing this notebook, and extracts of them are in this repository:
1. [anastasiialobanova's implementation of the paper](https://www.kaggle.com/code/anastasiialobanova/my-coatnet)
2. [xmu-xiaoma666's implementation of CoAtNet](https://github.com/xmu-xiaoma666/External-Attention-pytorch/blob/master/model/attention/CoAtNet.py)
3. [https://m0nads.wordpress.com/tag/self-attention/](https://github.com/xmu-xiaoma666/External-Attention-pytorch/blob/master/model/attention/CoAtNet.py)
4. [chinhsuanwu's implementation of CoAtNet](https://github.com/chinhsuanwu/coatnet-pytorch/blob/master/coatnet.py)
