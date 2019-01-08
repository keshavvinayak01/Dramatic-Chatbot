# Utils to download and read data for chat-bot training

This folder contains scripts for downloading, reading and preprocessing data for chat-bot training:
- `download_cornell.sh` - downloads Cornell movie dialogues dataset (small size)
- `download_opensubs.sh` - downloads Opensubs movie subtitles dataset (large size)
- `datasets.py` - module to be imported in your scripts, that exports functions for reading a dataset
- `example.py` - example of reading the dataset


Contains two instances of chatbots trained on the opensubs movie subtitiles data.

the datasets used by both of the notebooks is common, however the algorithms are slightly different:

###### 1. seq2seq model w/o attention.
###### 2. seq2seq with variational attention.

citations :  
[Bahdanau et al.2015] : In Proceedings of the International Conference on Learning Representations.

Variational Attention for Seq2Seq models (https://arxiv.org/pdf/1712.08207.pdf)



