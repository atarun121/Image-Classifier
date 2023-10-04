**Cats and Dogs Classification**

- In this Notebook, I have used Convolutional Neural Network to prepare the Model. The accuracy of the Model is in range of 80% on Training data and Validation data.

**Convolutional Neural Network**

- In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.


**Getting the Data**

- In this Project, I have downloaded the data using the link mentioned below. You can manually download the data from Kaggle. I am using Google Colab for this Project, so the act of reading the data might be different in different platforms.

~~~ cpp
!wget --no-check-certificate \
    "https://github.com/atarun121/Image-Classifier/blob/main/kagglecatsanddogs_5340.zip?raw=True" \
    -O "/tmp/PetImages.zip"
~~~
     

**Snapshot of the Data**

I have presented 8 pictures of cats and dogs which are present below: 



![image](https://github.com/atarun121/Image-Classifier/assets/79056939/9c78703b-7237-4cfd-a1e0-23a309dfb291)
















**Data Augmentation**

Data augmentation is a strategy that enables practitioners to significantly increase the diversity of data available for training models, without actually collecting new data. Data augmentation techniques such as cropping, padding, and horizontal flipping are commonly used to train large neural networks.

~~~
ImageDataGenerator(rescale=1./255,
                                   rotation_range=40,
                                   width_shift_range=0.2,
                                   height_shift_range=0.2,
                                   shear_range=0.2,
                                   zoom_range=0.2,
                                   horizontal_flip=True,
                                   fill_mode="nearest")
~~~
**Snapshot of the Loss and Accuracy score with Transfer learning** 

![image](https://github.com/atarun121/Image-Classifier/assets/79056939/b1b4c6d8-8ffd-4fe4-a70f-6ce595fcbed4)



















![image](https://github.com/atarun121/Image-Classifier/assets/79056939/9e52e918-51bd-4c00-950a-743eea138ec5)



















**Snapshot of the output of the Model**

![Screenshot 2023-10-05 004453](https://github.com/atarun121/Image-Classifier/assets/79056939/04e152f1-56f0-482b-946b-753823012a82)
