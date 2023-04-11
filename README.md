## CLVOS23: A benchmark dataset for addressing Continual Learning in Video Object Segmentation (VOS) and evaluating VOS models on long videos. 

***[🔥04.11.2023: Dataset has been released!]***
**[📄[Arxiv]](https://arxiv.org/abs/2304.04259)**

This repository contains information for the CLVOS23 dataset.

## Download

The frames of three videos [rat,dressage,blueboy] are from the Long Videos dataset, and are available to download separately from [Long Videos](https://www.kaggle.com/datasets/gvclsu/long-videos).

⬇️ Get the dataset from: 

 - ☁️ [***kaggle*** ](https://www.kaggle.com/datasets/amir4d/clvos23)


## File Structure

The dataset consists of two parts: `JPEGImages` which holds the frame images, and `Annotations` which contains the corresponding segmentation masks. The frame images are numbered using five-digit numbers. Annotations are saved in color-pattlate mode PNGs like [DAVIS](https://davischallenge.org/).

The provided annotations are for the validation set and include the first and the last frame.
The details of dataset are provided in following table.


| Video name  | \#Sub-chunks (tasks) | \#Frames | \#Annotated frames |
|-------------|----------------------|-----------|-------------------|
| dressage    | 23                   | 3589      | 43                |
| blueboy     | 27                   | 1416      | 47                |
| rat         | 22                   | 2606      | 42                |
| car         | 18                   | 1109      | 37                |
| dog         | 12                   | 891       | 25                |
| parkour     | 24                   | 1578      | 49                |
| skating     | 5                    | 778       | 11                |
| skiing      | 5                    | 692       | 11                |
| skiing-long | 9                    | 903       | 19                |

## Videos in YouTube
Follwing videos from YouTube are used to creat CLVOS23:

[car](https://www.youtube.com/watch?v=R70NIzexFOM),
[dog](https://www.youtube.com/watch?v=3JtnAEIPuoo),
[parkour](https://www.youtube.com/watch?v=vuedCe4r1-4),
[skating](https://www.youtube.com/watch?v=S-csVMqf2rc),
[skiing](https://www.youtube.com/watch?v=krkkTuNxZt8&t=2s),
[skiing-long](https://www.youtube.com/watch?v=XnQK4oVuFAk&t=622s).

## BibTeX
Please consider to cite CLVOS23 and Long Videos (for rat, dressage, and blueboy) if it helps your research.

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

CLVOS23 is licensed under a [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/) License.
[car, dog, parkour, skating, skiing, skiing-long] as you can see in the provided video links in youtube are under CC license in YouTube.
[rat, dressage,blueboy] are under Long Videos dataset license.
