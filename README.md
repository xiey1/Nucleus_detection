# Nucleus_detection
Automate nucleus detection

Datasets obtained from https://www.kaggle.com/c/data-science-bowl-2018/overview

# Project Aim:
### Build an algorithm to automate the process of identifying nuclei
<img src='https://github.com/xiey1/Nucleus_detection/blob/master/images/Image_visualization_eda.png' width=900px>

# Approach -- UNet
<img src='https://github.com/xiey1/Nucleus_detection/blob/master/images/u-net-architecture.png' width=900px>

<br>reference:
<br>https://arxiv.org/pdf/1505.04597.pdf
<br>https://github.com/milesial/Pytorch-UNet/tree/master/unet

# Result

<img src='https://github.com/xiey1/Nucleus_detection/blob/master/images/Image_visualization_train_1.png' width=900px>

<img src='https://github.com/xiey1/Nucleus_detection/blob/master/images/Image_visualization_test.png' width=900px>

<br>Remove nuclei with small size (possibly debris) and visualize nuclei using multi-channel imaging
<img src='https://github.com/xiey1/Nucleus_detection/blob/master/images/Image_visualization_multichannel.png' width=600px>

<br>Visualize individual detected nucleus
<img src='https://github.com/xiey1/Nucleus_detection/blob/master/images/Image_visualization_individual.png' width=900px>
