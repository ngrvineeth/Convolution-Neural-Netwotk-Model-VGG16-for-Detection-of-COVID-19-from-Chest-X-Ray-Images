# Convolution-Neural-Netwotk-Model-VGG16-for-Detection-of-COVID-19-from-Chest-X-Ray-Images

Datasets:
The dataset used in our work was obtained from the following:
i. Covid X-Ray Image Dataset - https://github.com/ieee8023/covid-chestxray-dataset for positive cases.
ii. Kaggle X-Ray Chest Image-https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia for negative cases.

We used frontal-view chest X-ray images in our research. The only X-ray views obtained were the posterior-anterior (PA) views. We divided the samples into two groups: COVID-19 patients with X-ray images and stable patients with X-ray images. The classes in the dataset are evenly distributed, with 196 images in each class for a total of 392 images in the dataset. The COVID-19 class in the dataset is made up of 196 chest X-ray images of patients diagnosed with COVID-19 that were gathered from various sources. On March 31, 2020, both of these sources were accessed. They are made up of X-ray images gathered from various journals, databases, and other sources. For this dataset, we used the collection of healthy patients' chest X-ray images from the Kaggle challenge "Chest X-ray Images (Pneumonia)". We chose 196 samples at random from the “normal” X-ray images, which correspond to healthy patients. This source was chosen because it has been frequently referenced in studies that suggest COVID-19 detection methods in X-rays.
