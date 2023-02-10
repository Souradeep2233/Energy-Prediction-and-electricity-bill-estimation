
## Predicting energy consumption and electric bill estimation using Time Series Forecasting.


Using Time Series Forecasting , we can study the pattern of energy Consumptionin in a general household , which can predict the estimated energy and cost in  next few weeks or months even,  with accuracy depending on nature of change in energy consumption and training data set.

In real time deployment , more number of days pass by , hence gathering more training data , accuracy drastically improves.

IOT sensors have been used to collect the raw data to cloud and  the entire project has been based on real time data with minimal latency possible to improve model's performance.

 

## Glimpses

![image](https://user-images.githubusercontent.com/94059815/218089410-a8434a15-43a3-4fb8-b9f7-872e560503d0.png)


## Requirements
1. Python 3.9+

2. Jupiter notebook (/support)

We highly recommend to use  only officially support the latest patch release of Python . Previous versions of Python may support ,however  not tested officially!

Some required deep learning frame works and other components :
    
    1. Pytorch
    2. Numpy
    3. scikit-learn
    4. Matplotlib
    5. Pandas
![download](https://user-images.githubusercontent.com/94059815/218092771-4c5b0c25-bc2c-40a9-b013-4f4be1694398.png)
![download](https://user-images.githubusercontent.com/94059815/218092916-1df20d8e-6f25-4734-8634-deb5b2ccff53.png)
![download](https://user-images.githubusercontent.com/94059815/218092992-ee172114-f7f0-4af5-8b6a-8d97ed284f6b.png)
![download](https://user-images.githubusercontent.com/94059815/218093074-a2a0b9af-7455-49e4-afc2-20cf07e74338.png)
![download](https://user-images.githubusercontent.com/94059815/218093155-50f9f8f8-d147-4af1-ad27-086034bb54ea.jpg)


However, the path/ location of the readings must be modified  before running the .ipynb file .
## Installation

Install using 'pip'...
    
    1. pip install torch
    2. pip install scikit-learn
    3. pip install numpy
    4. pip install matplotlib
    5. pip install pandas

## Dataset
The datset here named Energy Reading.csv has been prepared in real time using IOT sensors. Here, the time column represent the time in seconds at which data from IOT sensors reach the cloud . And the power is given in terms of Watt.

## Execution
You can directly run the .ipynb file in Jupiter notebook, only after modifying the path of the existing data set in local system and all the requirements being correctly met.

You can also use the weights provided in .pt file , by intialising an instance to class LSTM and accessing the weights to use in different applications as directed in "Loading the weights" cell of the .ipynb file.
## Authors

The code has been solely developed by Souradeep Dutta , an aspiring machine learning enginner and researcher.
Kindly share your feedback and do contribute and suggest for better performance of the model and mutual development 😊.

