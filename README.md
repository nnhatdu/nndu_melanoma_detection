# MELANOMA DETECTION

## Problem Statement
    Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
    
    The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

    The data set contains the following diseases:
    - Actinic keratosis
    - Basal cell carcinoma
    - Dermatofibroma
    - Melanoma
    - Nevus
    - Pigmented benign keratosis
    - Seborrheic keratosis
    - Squamous cell carcinoma
    - Vascular lesion
    
## Conclusions
- Conclusion 1 from the analysis   
    The model is overfitting because we can also see difference in loss functions in training & test around the 10-11th epoch.
    The accuracy is just around 75-80% because there are enough features to remember the pattern.
- Conclusion 2 from the analysis
    There is no improvement in accuracy but we can definitely see the overfitting problem has solved due to data augmentation
- Conclusion 3 from the analysis
    Accuracy on training data has increased by using Augmentor library
    Model is still overfitting
    The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
    The Model can be further improved by tuning the hyperparameter