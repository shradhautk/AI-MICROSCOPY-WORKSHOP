# AI-MICROSCOPY-WORKSHOP
Jupyter notebooks to be used in [AI MICROSCOPY WORKSHOP AT UTK](https://microscopyai.utk.edu/)

In Day2_Education_Day:
- CNN_tutorial - U-Net and Mask R-CNN notebooks, data
- Data_Augmentation - Data augmentation notebook, data, slides
- Data_Labeling - Data labeling notebooks, data, slides, supplementary docs
- VAE - VAE and DKL unsupervised learning notebooks 
- Kory's Session - Feature extraction and data visualization notebook 

Main Colab notebooks for the tutorials:
- DL_for_Microscopy_Data_Labeling.ipynb includes a workflow and scripts for parsing .xml files and turning them into masks/labels in the right format for U-Net and Mask R-CNN
- DL_for_Microscopy_Data_Augmentation.ipynb includes a workflow and scripts for performing sliding window transformation on original images/masks and adding augmentations, including transformations and noises, to enhance the dataset for U-Net and Mask R-CNN.
- DL_for_Microscopy_U_Net.ipynb includes a workflow for performing semantic segmentation of bubbles in TEM images using a U-Net via the AtomAI package.
- DL_for_Microscopy_Mask_R_CNN.ipynb includes a workflow for performing instance segmentation of bubbles in TEM images using Mask R-CNN implemented in PyTorch.
- rVAE.ipynb includes a workflow for performing invariant VAE analysis on a toy (MNIST) dataset, enabled by AtomAI.
- DKL.ipynb includes examples of implementation of DKL analysis via AtomAI.
- Feature Extraction.ipynb includes examples of extracting segmented features using thresholding methods and examples of data visualization techniques.
