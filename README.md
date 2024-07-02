# keyboard-acoustic-side-channel-attack-coatnet
This repo contains an implementation of the paper [A Practical Deep Learning-Based Acoustic Side
Channel Attack on Keyboards](https://arxiv.org/pdf/2308.01074).

The implementation of CoAtNet and the training of the model is in `keyboard-side-channel.ipynb`, while the algorithm for isolating keystrokes from recordings is implemented in `isolate_key_presses.py`.

# `isolate_key_presses.py` usage
```
python isolate_key_presses.py <path to recording> <number of keystrokes> 
    --init_treshold <initial energy threshold for detecting keystrokes> 
    --step < initial step by which to change the energy treshold> 
    --prefix <path to the directory where the isolated keystrokes will be stored>
```

# Acknowledgments
I have found these resources useful while writing this notebook, and extracts of them are in this repository:
1. [anastasiialobanova's implementation of the paper](https://www.kaggle.com/code/anastasiialobanova/my-coatnet)
2. [xmu-xiaoma666's implementation of CoAtNet](https://github.com/xmu-xiaoma666/External-Attention-pytorch/blob/master/model/attention/CoAtNet.py)
3. [https://m0nads.wordpress.com/tag/self-attention/](https://github.com/xmu-xiaoma666/External-Attention-pytorch/blob/master/model/attention/CoAtNet.py)
4. [chinhsuanwu's implementation of CoAtNet](https://github.com/chinhsuanwu/coatnet-pytorch/blob/master/coatnet.py)
