# BEVFormer

<div align="center">
  <img width="100%" alt="QueryInst-VIS Demo" src="figs/video.gif">
</div>

The official implementation of the paper "[BEVFormer: Learning Bird's-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers](https://arxiv.org/abs/todo)".

Authors: [Zhiqi Li](https://scholar.google.com.hk/citations?user=H2fJLqEAAAAJ&hl=zh-CN)\*, [Wenhai Wang](https://whai362.github.io/)\*, [Hongyang Li](https://lihongyang.info/)\*, [Enze Xie](https://xieenze.github.io/), [Chonghao Sima](https://scholar.google.com.hk/citations?user=dgYJ6esAAAAJ&hl=zh-CN&oi=ao), [Tong Lu](https://cs.nju.edu.cn/lutong/index.htm), [Yu Qiao](https://scholar.google.com/citations?user=gFtI-8QAAAAJ&hl=zh-CN), [Jifeng Dai](https://jifengdai.org/)

Code will be released around June 2022. 

# News
[2022/3/10]: We achieve the SOTA on [nuScenes Detection Task](https://nuscenes.org/object-detection?externalData=all&mapData=all&modalities=Camera) with **56.9% NDS** (camera-only)!
</br>


# Abstract
In this work, we present a new framework termed BEVFormer, which learns unified BEV representations with spatiotemporal transformers to support multiple autonomous driving perception tasks. In a nutshell, BEVFormer exploits both spatial and temporal information by interacting with spatial and temporal space through predefined grid-shaped BEV queries. To aggregate spatial information, we design a spatial cross-attention that each BEV query extracts the spatial features from the regions of interest across camera views. For temporal information, we propose a temporal self-attention to recurrently fuse the history BEV information.
Our approach achieves the new state-of-the-art **56.9\%** in terms of NDS metric on the nuScenes test set, which is **9.0** points higher than previous best arts and on par with the performance of LiDAR-based baselines.
# Results
![SOTA results](figs/sota_results.png "results on nuScenes")


# Methods
![method](figs/arch.png "model arch")



# Bibtex
If you find our work helpful for your research, please consider citing the following BibTeX entry.   
```
@misc{li2022bevformer,
      title={BEVFormer: Learning Bird's-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers}, 
      author={Zhiqi Li and Wenhai Wang and Hongyang Li and Enze Xie and Chonghao Sima and Tong Lu and Yu Qiao and Jifeng Dai},
      year={2022},
      eprint={todo},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
