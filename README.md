# Applied Data Science @ Columbia
## Fall 2024
## Project 2: How do cells respond to different drug treatment

### [Project Description]

Term: Fall 2024

+ Projec title: Predict the type of drug treatment based on aggregated microscopy images
+ Project description: This project explores the response of cells to various drug treatments using machine learning and image analysis techniques. The study utilizes a dataset derived from the CPJUMP1 experiments, as detailed in the work by Chandrasekaran et al. (2024), involving large-scale cellular imaging. The original dataset comprises 22,000 images from eight fluorescently labeled channels. However, for this project, a filtered subset of 2,867 images was provided. These images were median-aggregated across the first three channels to enhance robustness and facilitate downstream segmentation tasks. A multi-modal approach was implemented, combining image data (mask and flow images) processed through modified EfficientNet-based convolutional neural networks (CNNs) and tabular features processed through a fully connected network.
+ This project is conducted by Jiahui Zhu

This folder is orgarnized as follows.

```
proj/
├── notebook/
├── doc/report
└── output/best_model.pth
```
