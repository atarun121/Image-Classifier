**Cats and Dogs Classification**

- In this Notebook, I have used Convolutional Neural Network to prepare the Model. The accuracy of the Model is in range of 80% on Training data and Validation data.

**Convolutional Neural Network**

- In deep learning, a convolutional neural network is a class of deep neural networks, most commonly applied to analyzing visual imagery. They are also known as shift invariant or space invariant artificial neural networks, based on their shared-weights architecture and translation invariance characteristics.

**Getting the Data**

- In this Project, I have downloaded the data using the link mentioned below. You can manually download the data from Kaggle. I am using Google Colab for this Project, so the act of reading the data might be different in different platforms.

!wget --no-check-certificate \

`    `"https://download.microsoft.com/download/3/E/1/3E1C3F21-ECDB-4869-8368-6DEBA77B919F/kagglecatsanddogs\_3367a.zip" \

`    `-O "/tmp/cats-and-dogs.zip"

**Snapshot of the Data**

I have presented 8 pictures of cats and dogs which are present below: 


















**Data Augmentation**

Data augmentation is a strategy that enables practitioners to significantly increase the diversity of data available for training models, without actually collecting new data. Data augmentation techniques such as cropping, padding, and horizontal flipping are commonly used to train large neural networks.

ImageDataGenerator(rescale=1./255,

`                                   `rotation\_range=40,

`                                   `width\_shift\_range=0.2,

`                                   `height\_shift\_range=0.2,

`                                   `shear\_range=0.2,

`                                   `zoom\_range=0.2,

`                                   `horizontal\_flip=True,

`                                   `fill\_mode="nearest")

**Snapshot of the Loss and Accuracy score with Transfer learning** 







































**Snapshot of the output of the Model**

