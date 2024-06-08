# OC4Seq: 

The `OC4Seq` repository contains code for a multi-scale one-class recurrent neural network for detecting anomalies in discrete event sequences. The method implemented here is described in [this paper](https://dl.acm.org/doi/10.1145/3447548.3467125).

## Usage
- exp.py: This is the main experiment script
- model.py: The OC4Seq is implemented in the this file
- trainer.py: It implements the training producedure
- utils.py: It preprocesses the data for experiment

## Authors

- Zhiwei Wang
- Zhengzhang Chen
- Jingchao Ni
- Hui Liu
- Haifeng Chen
- Jiliang Tang

## Citation

If you find the code in this respository useful for your research, please cite our paper:
```
  @inproceedings{WangCNLCT21,
  author    = {Zhiwei Wang and
               Zhengzhang Chen and
               Jingchao Ni and
               Hui Liu and
               Haifeng Chen and
               Jiliang Tang},
  title     = {Multi-Scale One-Class Recurrent Neural Networks for Discrete Event
               Sequence Anomaly Detection},
  booktitle = {{KDD} '21: The 27th {ACM} {SIGKDD} Conference on Knowledge Discovery
               and Data Mining, Virtual Event, Singapore, August 14-18, 2021},
  pages     = {3726--3734},
  publisher = {{ACM}},
  year      = {2021}
}
```

## License

Creative Commons Attribution-NonCommercial (CC BY-NC) 4.0 International License

The OC4Seq is released under a CC BY-NC 4.0 International License:
https://creativecommons.org/licenses/by-nc/4.0.

NonCommercial — You can not use the code for commercial purposes.
