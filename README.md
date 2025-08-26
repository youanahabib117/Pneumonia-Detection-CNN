# Pneumonia-Detection-CNN

## Data
Dincer, T. (n.d.). Labeled chest X-ray images [Data set]. Kaggle. https://www.kaggle.com/datasets/tolgadincer/labeled-chest-xray-images

Pneumonia is a serious lung infection that is a leading cause of death in children under 5 years of age. The presence of this disease can be confirmed using chest X-rays. This dataset contains over 5,000 images of chest X-rays, sourced from Guangzhou Women and Children's Medical Center in China, that are either categorized as normal, bacterial pneumonia, or viral pneumonia. For simplicity, this project will focus on detecting the presence or absence of pneumonia, disregarding whether the pneumonia is bacterial or viral. This dataset is already split into a training and testing set.

For this project, we will try to find the best convolutional neural network architecture that is able to detect the presence of pneumonia based on chest X-ray images. Keras from Tensorflow will be used. Our objective is to be able to detect the presence of this disease with sufficient accuracy while also putting emphasis on the recall score to minimize the risk of failing to identify patients with pneumonia.
