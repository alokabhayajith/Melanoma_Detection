## Melanoma detection assignment
> The aim of the project is to build a CNN model to detec whether the given image is indicating melanoma or any other skin disease. Thus the project is a multi class image  classification problem.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Steps Performed](#steps-performed)
* [Conclusions](#conclusions)



## General Information
- The project aims to identify the class of skin disease based on the image data.
- The project is a part of the curriculum of upGrad's IIIT Bangalore EPGP in Machine Learning and Artificial Intelligence.


## Steps Performed
- Importing the necessary libraries.
- Importing the dataset to google drive as colab was used.
- Creating tensor datasets for training, validation and testing using image_dataset_from_directory keras function.
- Sequential model created with 1 rescaling layer, 3 convolutional layers and  3 max polling layes, 1 flattening layer and 2 dense layers.
- Augmenter library used because there was a class imbalance.
- New sequential model created with 1 rescaling layer, 3 convolutional layers and  3 max polling layes, 1 flattening layer and 2 dense layers using the augmented dataset.
    
    
## Conclusions
- Due to class imbalance the validation accuracy of the CNN model is not as good as the training accuracy.
- To improve validation accuracy augmentation strategies can be used and thus validation accuracy can be improved.



## Technologies Used
- numpy - version 1.26.4
- tensorflow - version 2.17.0
- matplotlib - version 3.7.1
- keras - version 3.4.1
- augmenter - version 0.2.12
- PIL - version 9.4.0



## Contact
Created by [@alokabhayajith] - feel free to contact me!