# Disease Identification of Apple Leaves
### Capstone Project - Alex & Brian

![screenshot](https://i.ibb.co/MZBy01P/header.png)

### Description: 
Based on a competition from Kaggle in 2020, we use deep learning models to perform image classification and localization on photos of apple leaves. Our objective was to assess the health of each leaf and plot the location of the leaf in the image.

### Motivation: 
Failing to properly diagnose diseases on agricultural crops can lead to the misuse of chemicals and the emergence of resistant pathogen strains. This has dire concequences for input costs and environmental impacts. Currently, disease diagnosis is done by humans scouting around the crop fields. This is time-consuming and expensive. Computer-vision based models have the promise to increase the efficiency and accuracy of this process. In this project's case, the crops being diagnosed are the leaves on apple trees.

### Conclusions: 
This project showed that the health of apple leaves can be efficiently diagnosed by a CNN model, assuming it is given a clear, quality photo of the leaf. Our model was able to achieve a disease classification accuracy of 95.5%, and other models in Kaggle's competition went as far as achieving 98%, which shows that these types of models can be very accurate at idenitfying the disease on each leaf. We also proved that it was feasible to locate the leaf in the image, with further improvements needed in future to train the model on far more images annotated with bounding boxes. Using just 500 training images gave us a reasonable localization model, thus training a model on thousands of training images in the future would be very promising in it's accuracy.

Overall, we conclude that a fairly simple convolutional neural network is sufficient to classify the diseases present on apple leaves, as well as locate the leaves in the photo. Additional work is required in future to further improve the accuracy of both classification and localization, by training models on a much wider range of training images to improve the generalisation and robustness of our models. 

_Some sample leaf images being classified/localized by our models:_

![screenshot](https://i.ibb.co/cLJcrqQ/examples.png)

(Kaggle competition that this project is based on: https://www.kaggle.com/c/plant-pathology-2020-fgvc7/overview)

---

This repository contains our capstone project notebooks, saved model files and presentation. 

The dataset we used is too large to be stored in this repository, but it can be downloaded from Kaggle here: https://www.kaggle.com/c/plant-pathology-2020-fgvc7/data

You will have to unzip the downloaded dataset in this root folder if you wish to rerun any of the notebooks, as well as unzipping the two model files.
