<!--
title: 'Image Classification using Feature Descriptors'
description: 'This repositry contain jupyter notebooks that were used to classify objects using feature descriptrs. We have used SIFT and ORB to train classifiers like SVM and Random Forests.'
layout: Doc
language: python
authorLink: 'https://github.com/MrDexxter/'
authorName: 'Ahmad, inc.'
-->

![cute fluffy monster with black background](https://user-images.githubusercontent.com/97404986/224576815-de4444ab-0d57-4181-a3a2-7e96d0e403c1.jpg)

# Classification with Feature Descriptors (SIFT & ORB)

The files uses OpenCV pipelines to detect and describe the features of an image. It then uses classifiers like SVM and Random Forest to classify them.

## Needed Packages
You will need opencv, sklearn, numpy and matplotlib to run these files. You can install those packages from pip using the following code:
```bash
pip install scikit-learn
pip install numpy
pip install matplotlib
pip install opencv-python
```

### File Information
The project contain two .ipynb files. One for Object dataset and other for flower dataset. You can run the jupyter notebooks using google colab or any other python IDLE.

### Results
The SVC classifier did well on the object dataset with an accuracy of 75 percent. Random forest was able to achieve an accuracy of 62 percent. However, these methods failed drastically on the flower dataset. The accuracy was not more than 50 percent with either classifier. This accounts for variance in each category of flowers and a large number of data samples. 
