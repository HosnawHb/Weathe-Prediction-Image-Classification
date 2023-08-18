# Weather Prediction Image Classification
👋 Hey there!
In this project, I worked with the Multi-class Weather Dataset 🌦️. <br />
This dataset consists of four main classes: 🌧️ Rain, ☀️ Shine, 🌅 Sunrise, and 🌥️ Cloudy. For more detailed information about this dataset, you can check out [Multi-Class Weather Dataset](https://www.kaggle.com/datasets/pratik2901/multiclass-weather-dataset).<br />
The purpose of this project was to get familiar with computer vision ,image processing and deep convolutional neural networks.<br />
To better understand the dataset, the following steps were performed: <br /> <br />
1️⃣ Import and check the dataset:</br >
Analyzing the dataset by examining the number of images available and the data distribution among each class. Additionally, the varying dimensions of the images and devise appropriate strategies to handle them was considered.<br /> <br />
2️⃣ Dataset split:</br >
The dataset was randomly divided into an 80% training set and a 20% testing set. <br /> <br />
3️⃣ Model development and training:</br >
Different models using deep learning libraries were designed and implemented. Beginning with a deep neural network consisting of dense or fully connected layers. The number of layers gradually increased, and various activation functions were tested leading to choosing the best model by performance comparison. </br > </br >
4️⃣ ResNet model implementation: </br >
A model was designed based on the ResNet architecture, with a minimum of four residual blocks. Multiple architecture configurations was explored, along with hyperparameter choices, in order to achieve the best results. </br > 
<div align="center"><img src="https://github.com/HosnawHb/Weather-Prediction-Image-Classification/blob/main/ResNet.png?raw=true"width="60%"/></div> </br >
5️⃣ Inception Network implementation: </br >
Cues were taken from the Inception Network, with a minimum of three Inception modules. Similar to the previous step, various architecture designs and hyperparameter settings were tested. </br > </br >
6️⃣ Model evaluation with k-fold cross-validation:</br >
From the top-performing models in terms of accuracy, three models were selected for evaluation using k-fold cross-validation with k=5. Alongside evaluation metrics, the Confusion Matrix is visualized to provide further insights. </br > </br >
Feel free to explore the repository and refer to the detailed report for more information on the dataset analysis, model development, and evaluation results.











