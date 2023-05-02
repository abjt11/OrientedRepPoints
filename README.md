# Oriented RepPoints for Aerial Object Detection

# Installation
Either refer to ![install.md](https://github.com/LiWentomng/OrientedRepPoints/blob/main/docs/install.md) for installation and dataset preparation or build a conda environment from orp_env.yml


# Getting Started 
Please see ![getting_started.md](https://github.com/LiWentomng/OrientedRepPoints/blob/main/docs/getting_started.md) for the basic usage.

# Results and Models
The results on DOTA test set are shown in the table below. More detailed results please see the paper.

  Model| Backbone  |data aug(HSV+Rotation)| mAP | model| log
 ----  | ----- | ------ |------| ------ | ------  
 OrientedReppoints| R-50|  |75.97 |[model](https://drive.google.com/file/d/13c56u9IFRRdHH-YNmQfqb1y11f7xPfCR/view?usp=sharing) | [log](https://drive.google.com/file/d/1_lrj3gV27iM0v95AnSCRHUZDZWkdJFS_/view?usp=sharing)
 OrientedReppoints| R-101| |76.52 |[model](https://drive.google.com/file/d/1otXS3w0LVopsBKxyYbyQhF6mFDtTIJFX/view?usp=sharing) | [log](https://drive.google.com/file/d/1MgJ7A9INaP3iocy1MQSS1SA6gyIvnTJX/view?usp=sharing)
 OrientedReppoints| Swin-Tiny|  √  | 78.11|[model](https://drive.google.com/file/d/1B03dBSXU9GFGRM8XiyQo2aw6yGnCgB8r/view?usp=sharing) | [log](https://drive.google.com/file/d/1lt5UkBPVM7am6asySRWohXSRK_tGwxV8/view?usp=sharing)

# Few Shot Learning with OrientedRepPoints on Omniglot Data

1. Place the data folder according to the notebook data folder setting or configure the data path
2. Run the jupyter notebook FSL_OrientedRepPoints_Omniglot.ipynb

# Few Shot Learning with OrientedRepPoints on our Custom Energy Infrastructure Data

1. Place the data folder according to the notebook data folder setting or configure the data path
2. Run the jupyter notebook FSL_OrientedRepPoints_Custom.ipynb


#  Acknowledgements
Here are some great resources we benefit. We would espeicially thank the authors of:

[MMdetection](https://github.com/open-mmlab/mmdetection)

[RepPoints](https://github.com/microsoft/RepPoints)

[AerialDetection](https://github.com/dingjiansw101/AerialDetection)

[BeyondBoundingBox](https://github.com/sdl-guozonghao/beyondboundingbox)




