# Bin_with_a_Brain

## General info
The project contains waste classification with Convolutional Neural Networks (CNN) algorithms to determine if the waste may be recycled or not. The analysis has been made in the approach that includes CNN model with data augmentation to achieve the better results.

**A classifier simulation application is created in Streamlit based on this trained CNN model and is available [here](https://github.com/nightKnight112/Bin_with_a_Brain/tree/main/api-cfg/app.py) . The code for this app is [here](https://github.com/nightKnight112/Bin_with_a_Brain/tree/main/api-cfg).**

### Dataset
The dataset contains the 22500 images of organic and recyclable objects. It comes from Kaggle and can be find [here](https://www.kaggle.com/techsash/waste-classification-data).


## Motivation
The aim of the project is waste classification by using Deep Neural Networks. The dataset contains recyclable waste images and organic waste images split into TEST and TRAIN dirs. We had built a model to predict if the waste would be recyclable or not. In our analysis we used Convolutional Neural Network (CNN) model with data augumentation to get more accurate predictions and choose the best one amongst the models for our purpose.

## Project includes:

* Waste Classification with CNN Model and data augmentation - **Model_p_final.ipynb**
* The final saved/deployed model - **bin_witha_brain_modelf.h5**
 
## Technologies

The project is created with:
* **Python** version 3.10.5
* **Libraries:** TensorFlow, Keras, numpy, pandas, matplotlib, zipfile, seaborn, PIL.

**Running the project:**

To run this project use Jupyter Notebook or [Google Colab](https://colab.research.google.com/drive/1EZkDLuk8S9Zzn90dlKIoQZ7T7VUshjk0?usp=sharing).<br /><br />
**Alternatively,** <br /> The program can also be run on any IDE by opening the **[Model_p_final.ipynb](https://colab.research.google.com/drive/1EZkDLuk8S9Zzn90dlKIoQZ7T7VUshjk0?usp=sharing)** file in Google Colab and importing the whole code as a **.py** file.</br>

To run the model trainer locally, install the packages: 
```
pip install -r requirements.txt
```
or install the libraries using the following commands</br>
```
pip install tensorflow
pip install keras
pip install numpy
pip install pandas
pip install pillow
pip install matplotlib
pip install seaborn
```
Also, one can find the model training and testing workflow and software simulation workflow [here](https://whimsical.com/mini-project-re-QcrHkkrnrr52aCwB7eE3e)
The deployed app can be accessed [here](https://nightknight112-bin-with-a-brain-api-cfgapp-qt2ylc.streamlit.app/)
