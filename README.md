# Bird Segmentation with a Pretrained ResNet Encoder and U-Net Decoder

This project focuses on segmenting birds from natural images using a segmentation model that combines a pretrained ResNet-50 encoder with a U-Net-like decoder. Through data augmentation, hyperparameter tuning, and careful training, the model achieves an Intersection over Union (IoU) score above 60%, ultimately reaching about 64%.

## Project Overview

Wildlife image segmentation often encounters challenges due to complex backgrounds, variable lighting, and diverse bird appearances. By leveraging transfer learning (pretrained ResNet-50), U-Net-inspired architectures, and data augmentation, this project demonstrates that robust segmentation performance can be achieved.

**Key Features:**
- Uses a pretrained ResNet-50 encoder for robust feature extraction.
- U-Net-style decoder to combine multi-scale features and preserve spatial details.
- Data augmentation (flips, rotations, color jitter) to improve generalization.
- Achieves over 64% IoU on the test set, surpassing the initial 60% goal.

  
