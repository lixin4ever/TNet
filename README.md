# TNet
**T**ransformation **Net**works for Target-Oriented Sentiment Classification. (Currently, code is only available upon request)

## Requirements
* Python 3.6
* Theano 0.9.0
* numpy 1.13.1
* pygpu 0.6.9
* GloVe.840B.300d

## Running
```
THEANO_FLAGS="device=cuda0, optimizer=fast_compile" python main.py -ds_name [YOUR_DATASET_NAME] -connection_type [AS|LF]
```

## Environment
* OS: REHL Server 6.4 (Santiago)
* GPU: NVIDIA GTX 1080
* CUDA: 9.2
* cuDNN: v7.1.4


## Citation
If the code is used in your research, please star our repo and cite our paper as follows:
```
@inproceedings{li2018transformation,
  title={Transformation Networks for Target-Oriented Sentiment Classification},
  author={Li, Xin and Bing, Lidong and Lam, Wai and Shi, Bei},
  booktitle={ACL},
  pages={946--956},
  year={2018}
}
```
