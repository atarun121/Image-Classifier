**Cats and Dogs Classification**

- In this Notebook, I have used Convolutional Neural Network to prepare the Model. The accuracy of the Model is in range of 80% on Training data and Validation data.

**Convolutional Neural Network**

- In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.

**Getting the Data**

- In this Project, I have downloaded the data using the link mentioned below. You can manually download the data from Kaggle. I am using Google Colab for this Project, so the act of reading the data might be different in different platforms.

!wget --no-check-certificate \
    "https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs_3367a.zip" \
    -O "/tmp/cats-and-dogs.zip"

**Snapshot of the Data**

I have presented 8 pictures of cats and dogs which are present below: 



![image](https://github.com/atarun121/Image-Classifier/assets/79056939/9c78703b-7237-4cfd-a1e0-23a309dfb291)
















**Data Augmentation**

Data augmentation is a strategy that enables practitioners to significantly increase the diversity of data available for training models, without actually collecting new data. Data augmentation techniques such as cropping, padding, and horizontal flipping are commonly used to train large neural networks.

ImageDataGenerator(rescale=1./255,
                                   rotation_range=40,
                                   width_shift_range=0.2,
                                   height_shift_range=0.2,
                                   shear_range=0.2,
                                   zoom_range=0.2,
                                   horizontal_flip=True,
                                   fill_mode="nearest")

**Snapshot of the Loss and Accuracy score with Transfer learning** 







































**Snapshot of the output of the Model**

