# Event Camera Demosaicing via Swin Transformer and Pixel-focus Loss

## Overview
This repository contains the official implementation of our paper "Event Camera Demosaicing via Swin Transformer and Pixel-focus Loss," accepted at the CVPR Workshop 2024. Our work introduces a novel approach to demosaicing for event cameras using Swin Transformers coupled with a pixel-focus loss mechanism, significantly enhancing image reconstruction quality.

## Citation
If you find our work useful in your research, please consider citing:


```
@inproceedings{yourname2024event,
  title={Event Camera Demosaicing via Swin Transformer and Pixel-focus Loss},
  author={Your Name and Co-authors},
  booktitle={Proceedings of the CVPR Workshop},
  year={2024}
}
```

## Installation

Requirements
```
python 3.8+
torch 1.8.0+
torchvision 0.9.0+
```
Other dependencies listed in requirements.txt

## Setup
Clone the repository and install the dependencies:

```bash
git clone https://github.com/yourgithub/event-camera-demosaicing.git
cd event-camera-demosaicing
pip install -r requirements.txt
```

## Dataset


### To train the model
```
python train.py --config configs/train_config.yaml
```

### To evaluate the model

```
python evaluate.py --config configs/eval_config.yaml --model_path /path/to/model.pth
```

## Pre-trained Models

Link to any pre-trained models you are providing, and instructions on how to use them.

## Acknowledgments

Thanks to these open source projects, which are vital for our proejct.
- VRT: https://github.com/JingyunLiang/VRT
- RSTT: https://github.com/llmpass/RSTT
- SwinIR: https://github.com/JingyunLiang/SwinIR
