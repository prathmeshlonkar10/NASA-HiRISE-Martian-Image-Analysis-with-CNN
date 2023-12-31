# NASA HiRISE Martian Image Analysis with CNN

![image](https://github.com/prathmeshlonkar10/NASA-HiRISE-Martian-Image-Analysis-with-CNN/assets/66990159/b0218603-1c6a-4077-b8c6-721d427fbbb0)


## Highlight
Martian HiRISE Dataset: https://dataverse.jpl.nasa.gov/dataset.xhtml?persistentId=doi:10.48577/jpl.QJ9PYA

This dataset was created to study Mars' seasonal frost cycle and its role in the planet's climate and surface evolution over the past ~2 billion years. Scientists are interested in identifying low-latitude frosted microclimates and their impact on climate, and future exploration of Mars will partially depend on finding potential habitable environments and resources for human explorers. Previous studies of Mars' seasonal frost cycle were limited by a trade-off between coverage and spatial resolution, as scientists were forced to take either a global perspective using coarse observations or a local perspective focused on higher-resolution observations. 

To overcome this limitation, data science techniques could be useful to identify frost at a global scale with both high-resolution visible and coarse resolution thermal datasets. Toward that goal, models are needed to help identify frost in large-scale, high-resolution imagery. The dataset provided here is meant to address that need. It contains high resolution visible data (from HiRISE on MRO) with frost labels, which can be used to train machine learning models for frost identification in large datasets. In this project, we are trying to build a model that distinguishes images of Martian terrain with frost using CNN image classification and transfer learning algorithms (EfficientNetB0, ResNet50, and VGG16)


## Key Aspects
- Data Augmentation and Pre-processing
- Data Visualization
- CNN-MLP model architecture
- Transfer Learning algorithms
- EfficientNetB0, ResNet50, VGG16
- Achieved 95% test accuracy
