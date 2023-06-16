<p align="center">
  <img src="https://github.com/CatCares/CatCares_CC/assets/133958617/32bea8d2-77d7-41f6-b219-742e21e204f2" alt="CatCares logo" height="200" />
</p>

<h1 align="center">MACHINE LEARNING - CAT CARES</h1>

<div align="center">

[![ML Contributors](https://img.shields.io/github/contributors/CatCares/CatCares_ML?color=blue)](#mlcontributors)
</div>

# Profile 

### Team ID : C23 - PR579

### Machine Learning Members :

* M210DSX3687 - Faiz Alana - Universitas Jenderal Soedirman
* M286DSY1473 - Anisa Nur Rahmawati - Universitas Negeri Semarang
* M181DSY2546 - Febrima Dola - Universitas Indonesia


# Machine Learning Project 

### Dataset :
We use this [Dataset.](https://drive.google.com/drive/folders/1qH0IgxUk5CcmJmTGipvNLBR9z_BK2syp?usp=drive_link) We're using from [roboflow](https://universe.roboflow.com/tain/cat-ringworm/dataset/3) and we also using dataset from multiple sources in internet.

### Model Architecture 
We designed a simple model using several sequential layers, namely several convolutional 2D layers, 2D max pooling, flatten layers and dense layers. The activation used is relu for the convolutional and max pooling layers, as well as sigmoid activation because the results of this classification are only one type. We use tensorflow for the sequential model.Before the model trains with the dataset, we perform augmentation techniques for the training and test datasets. We use binary class mode, then the loss used is binary crossentropy and the optimizer when training is RMSprop. After the model is created, we save it with the file type '.h5'.


This is the summary of the model 
<p align="center">
  <img width="400" height="350" src="https://github.com/CatCares/CatCares_ML/blob/main/Model%20Architecture.png">
</p>


We use this code to modify the dataset
<p align="center">
  <img width="400" height="450" src="https://github.com/CatCares/CatCares_ML/blob/main/Augmentasi.png">
</p>


### Graph After Training

This is the plot that has been run
<p align="center">
  <img width="400" height="350" src="https://github.com/CatCares/CatCares_ML/blob/main/Plot%20accuracy.png">
</p>

We get a high accuracy of around 95% and validation accuracy of around 90%.

### Conclusion
From this simple model and after testing with several objects, we succeed to detect the ringworm disease.

### How To Use
1. Download the [Dataset.](https://drive.google.com/drive/folders/1qH0IgxUk5CcmJmTGipvNLBR9z_BK2syp?usp=drive_link)
2. Unzip the dataset, then upload the dataset folder to Google Drive.
3. Copy the [code](https://github.com/CatCares/CatCares_ML/blob/main/Ringworm_Prediction.ipynb) by pressing "Open in colab"
4. Run the copied code and try it.
5. Download the [image](https://github.com/CatCares/CatCares_ML/tree/main/Test%20Images) to test the results of the run code.
