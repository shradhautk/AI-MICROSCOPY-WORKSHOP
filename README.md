# AI-MICROSCOPY-WORKSHOP
Jupyter notebooks to be used in [AI MICROSCOPY WORKSHOP AT UTK](https://microscopyai.utk.edu/)

In Day2_Education_Day:
- CNN_tutorial - U-Net and Mask R-CNN notebooks, data
- Data_Augmentation - Data augmentation notebook, data, slides
- Data_Labeling - Data labeling notebooks, data, slides, supplementary docs
- VAE - VAE unsupervised learning notebook

Main Colab notebooks for the tutorials:
- DL_for_Microscopy_Data_Labeling.ipynb includes a workflow and scripts for parsing .xml files and turning them into masks/labels in the right format for U-Net and Mask R-CNN
- DL_for_Microscopy_Data_Augmentation.ipynb includes a workflow and scripts for performing sliding window transformation on original images/masks and adding augmentations, including transformations and noises, to enhance the dataset for U-Net and Mask R-CNN.
- DL_for_Microscopy_U_Net.ipynb
- DL_for_Microscopy_Mask_R_CNN.ipynb
