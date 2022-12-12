# VideoHazing
Towards Robust Video-Dehazing: On the efficiency of SOTA models on the REVIDE dataset
##Objective
- Training of multiple SOTA models like AOD-Net, FFA-Net, Dehaze-Former on the REVIDE dataset
- Comparison of these models’ performance on the datasets they were originally trained on56
and the REVIDE dataset
- Development of a pipeline that can deconstruct videos into images, perform dehazing58
and reconstruct dehazed images into videos


# Datasets Used
- REVIDE (Zhang. et al, 2021), collection of a real-world video dehazing dataset containing pairs of real hazy and corresponding haze-free videos. (https://github.com/BookerDeWitt/REVIDE_Dataset)

# Code Bases Referred and Used
- AOD-Net (All-in-One Dehazing Network) is an image dehazing model built with a convolutional neural network (CNN). It is designed based on a re-formulated atmospheric scattering model. (https://github.com/MayankSingal/PyTorch-Image-Dehazing)
- DehazeFormer. It’s network architecture is a modification of the popular Swin Transformer (CITE). Given the image pair I(x), J(x), only the L1 loss needs to be computed to train DehazeFormer(https://github.com/IDKiro/DehazeFormer)
- FFA-Net model is an attention-based feature fusion (FFA) structure. This structure can retain shallow layers information and pass it to deep layers. (https://github.com/zhilin007/FFA-Net)
