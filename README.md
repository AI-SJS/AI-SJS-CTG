# CTG 후처리 모듈을 활용한 <br>Zero-Shot Open-Vocabulary Segmentation 개선 연구



<img width="1323" height="648" alt="image" src="https://github.com/user-attachments/assets/51b85df0-dc4a-4eb4-a9ee-da989556447a" />

## Installation

To get started, clone the repository and install dependencies:

```bash
!git clone --recurse-submodules https://github.com/AI-SJS/AI-SJS-CTG.git
%cd AI-SJS-CTG/GEM
!pip install -e .
```

## Requirements

```bash
- torch>=1.9.0
- torchvision
- regex
- ftfy
- tqdm
- huggingface_hub
- sentencepiece
- protobuf
- timm
- einops
- open_clip_torch<=2.23.0
- opencv-python
- matplotlib
- numpy
- requests
- torchmetrics
```

## Datasets
We use three datasets (Pascal VOC, ADE20K and OpenImages V7) in our paper.

For `Pascal VOC`, you can download the dataset from [here](https://www.kaggle.com/datasets/gopalbhattrai/pascal-voc-2012-dataset).

For `ADE20K`, you can download the dataset from [here](https://ade20k.csail.mit.edu/).

For `OpenImages V7`, you can download the dataset from [here](https://storage.googleapis.com/openimages/web/download_v7.html).



## Run on Pascal VOC

To reproduce the Pascal VOC experiments:

- **PascalVOC 재구현 코드**  
  Run: [`PascalVOC_재구현_코드.ipynb`](./PascalVOC_재구현_코드.ipynb)

- **PascalVOC + CTG 실험 코드**  
  Run: [`PascalVOC_+CTG_코드.ipynb`](./PascalVOC_+CTG_코드.ipynb)

- **PascalVOC Heatmap 시각화 코드**  
  Run: [`PascalVOC+heatmap_코드.ipynb`](./PascalVOC+heatmap_코드.ipynb)


---

## Run on ADE20K

To reproduce the ADE20K experiments:

- **ADE20K 재구현 코드**  
  Run: [`ADE20K_재구현_코드.ipynb`](./ADE20K_재구현_코드.ipynb)

- **ADE20K + CTG 실험 코드**  
  Run: [`ADE20K + CTG_코드.ipynb`](./ADE20K%20+%20CTG_%EC%BD%94%EB%93%9C.ipynb)

- **ADE20K Heatmap 시각화 코드**  
  Run: [`ADE20K+heatmap코드.ipynb`](./ADE20K+heatmap%EC%BD%94%EB%93%9C.ipynb)


  ---

## Run on OpenImages V7

To reproduce the OpenImages V7 experiments:

- **OpenImages V7 재구현 코드**  
  Run: [`ADE20K_재구현_코드.ipynb`](./ADE20K_재구현_코드.ipynb)

- **OpenImages V7 + CTG 실험 코드**  
  Run: [`ADE20K + CTG_코드.ipynb`](./ADE20K%20+%20CTG_%EC%BD%94%EB%93%9C.ipynb)


