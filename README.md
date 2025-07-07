# MRI Segmentation with ResNet

Automatic segmentation of T2-weighted brain MRI images using a modified ResNet architecture with SE-blocks.

## Dataset

Download `data.zip`:  
[Google Drive](https://drive.google.com/uc?export=download&id=16dysEMUrB_QshpdgXbQMKFIY_N91pHSj)

Or via terminal:

```bash
pip install gdown
gdown --id 16dysEMUrB_QshpdgXbQMKFIY_N91pHSj --output data.zip
unzip data.zip -d ./data
