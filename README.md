# CLVOS23: A benchmark dataset for addressing Continual Learning in VOS and evaluating VOS models on long videos. 

**[📄[Arxiv]](https://arxiv.org/abs/2302.01872)**

This repository contains information for the CLVOS23 dataset.


## Download

The frames of three videos [rat,dressage,blueboy] are from the Long Videos dataset, and are available to download from [Long Videos](https://www.kaggle.com/datasets/gvclsu/long-videos).


***[🔥04.07.2023: Dataset has been released!]***

⬇️ Get the dataset from: 

 - ☁️ [***kaggle*** ](https://entuedu-my.sharepoint.com/:f:/g/personal/liuc0058_e_ntu_edu_sg/EjXSfDF7QEZApAVpFJ5rfdABkHCf0k2Va6VDfUy7rpabNw?e=9BVkrz)


## File Structure

The dataset consists of two parts: `JPEGImages` which holds the frame images, and `Annotations` which contains the corresponding segmentation masks. The frame images are numbered using five-digit numbers. Annotations are saved in color-pattlate mode PNGs like [DAVIS](https://davischallenge.org/).

The provided annotations are for the validation set and include the first and the last frame.

```
<train/valid.tar>
│
├── Annotations
│ │ 
│ ├── <video_name_1>
│ │ ├── 00000.png
│ │ ├── 00001.png
│ │ └── ...
│ │ 
│ ├── <video_name_2>
│ │ ├── 00000.png
│ │ ├── 00001.png
│ │ └── ...
│ │ 
│ ├── <video_name_...>
│ 
└── JPEGImages
  │ 
  ├── <video_name_1>
  │ ├── 00000.jpg
  │ ├── 00001.jpg
  │ └── ...
  │ 
  ├── <video_name_2>
  │ ├── 00000.jpg
  │ ├── 00001.jpg
  │ └── ...
  │ 
  └── <video_name_...>

```


## BibTeX
Please consider to cite CLVOS23 and Long Videos if it helps your research.

```latex
@article{CLVOS23,
  title={CLVOS23: A Long Video Object Segmentation Dataset for Continual Learning},
  author={A. Nazemi, Z. Mostafa, P.Fieguth},
  journal={arXiv preprint arXiv:2302.01872},
  year={2023}
}

@article{liang2020video,
  title={Video object segmentation with adaptive feature bank and uncertain-region refinement},
  author={Liang, Yongqing and Li, Xin and Jafari, Navid and Chen, Jim},
  journal={Advances in Neural Information Processing Systems},
  volume={33},
  pages={3430--3441},
  year={2020}
}
```

## License
Follwing videos from YouTube are used for creating CLVOS23:


CLVOS23 is licensed under a [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) License. The data of CLVOS23 is released for non-commercial research purpose only.
