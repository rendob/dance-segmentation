# Automatic Dance Video Segmentation for Understanding Choreography

This repository contains the dataset used in the work "Automatic Dance Video Segmentation for Understanding Choreography," which is accepted in [MOCO '24](https://moco24.movementcomputing.org/).

## Links

- [Project page](https://shuhei2306.com/research/automatic_segmentation.html)
- [DOI: 10.1145/3658852.3659076](https://doi.org/10.1145/3658852.3659076)
- [arXiv: 2405.19727](https://arxiv.org/abs/2405.19727)

## Dataset

A dataset was constructed by manually annotating segmentation points for 1410 videos in the [AIST Dance DB](https://aistdancedb.ongaaccel.jp/).

The annotation data for basic videos are contained in `basic_*.csv`, and for advanced videos in `advanced_*.csv`.
The file `*_count.csv` represents segmentation points in counts (= musical beats), and the file `*_sec.csv` in seconds. You can use either one.

> [!Note]
> The count starts with 1. That is, the first beat in the video corresponds to count 1.

For each file, the first row is the header, and each remaining row corresponds to each annotation data.
For each row, the first column is the video URL, the second column is the annotator ID, and the remaining columns represent the annotated segmentation points.


## Terms of Use

All the contents in this repository can only be used for academic research purposes.
Please cite [our paper](https://doi.org/10.1145/3658852.3659076) when you use it.
