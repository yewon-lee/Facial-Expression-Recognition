# Facial-Expression-Recognition
ResNet-based facial expression classifier, trained and tested on FER2013, CK+, and KDEF datasets. 

This repo contains code used to pre-process and combine datasets. It also contains the model, training, and loss functions, as well as training curves. See organization below.

# Organization

```bash
│   .gitattributes
│
├───src
│   │   Data Augmentation and Preprocessing.ipynb
│   │   Data Loading - Sanity Check.ipynn
│   │   preprocess.py
│   │   Qualitative Results.ipynb
│   │   Resnet Model Training - No extraction.ipynb
│   │   train.py
│   │   util.py
│   │
│   ├───preprocessing_notebooks
│   │       CK_preprocess_and_save.ipynb
│   │       KDEF_preprocess_and_save.ipynb
│   │
│   └───__pycache__
│           preprocess.cpython-38.pyc
│           train.cpython-38.pyc
│           util.cpython-38.pyc
│
└───training_curves
    │   model_Resnet50-Pretrained-12000-Dropout_bs128_lr0_001_epoch5.png
    │   model_Resnet50-Pretrained-12000-Dropout_bs32_lr0_0001_epoch5.png
    │
    └───Old training curves
            model_Resnet50-Pretrained-12000-Dropout-Normalized_bs128_lr0_001_epoch5.png
            model_Resnet50-Pretrained-12000-Dropout-Normalized_bs32_lr0_001_epoch5.png
            model_Resnet50-Pretrained-12000-Dropout_bs128_lr0_001_epoch3.png
            model_Resnet50-Pretrained-12000-Dropout_bs128_lr0_001_epoch4.png
            model_Resnet50-Pretrained-12000-Dropout_bs128_lr0_001_epoch5.png
            model_Resnet50-Pretrained-12000-Dropout_bs16_lr0_0001_epoch10.png
            model_Resnet50-Pretrained-12000-NoDropout_bs128_lr0_001_epoch2.png
            model_Resnet50-Pretrained-NoCutoff_bs128_lr0_001_epoch1.png
            model_Resnet50-Pretrained-NoCutoff_bs128_lr0_001_epoch2.png
            model_Resnet50-Pretrained-NoCutoff_bs128_lr0_001_epoch5.png
```
