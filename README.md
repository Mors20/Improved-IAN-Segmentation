# Improved-IAN-Segmentation

The 2nd solution to Tooth Fairy: Cone-Beam Computed Tomography (CBCT) Segmentation Challenge. 

## Fine-tuning strategy
The code in fine_tuning.py is just an example for this fine-tuning strategy, we present a demo on a simple U-Net. But in pratice, the fine-tuning strategy is performed on nnU-Net.

## Focal Dice loss
The focal Dice loss is in loss_function.py which should be used combined with nnU-Net.

## Acknowledgements
This code repository refers to [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) and [Pytorch Medical Segmentation](https://github.com/MontaEllis/Pytorch-Medical-Segmentation)
