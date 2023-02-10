
## Predicting energy consumption and electric bill estimation using Time Series Forecasting.


Using Time Series Forecasting , we can study the pattern of energy Consumptionin in a general household , which can predict the estimated energy and cost in  next few weeks or months even,  with accuracy depending on nature of change in energy consumption and training data set.

In real time deployment , more number of days pass by , hence gathering more training data , accuracy drastically improves.

IOT sensors have been used to collect the raw data to cloud and  the entire project has been based on real time data with minimal latency possible to improve model's performance.

 

## Screenshots

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

However, the path/ location of the readings must be modified  before running the .ipynb file .
## Installation

Install using 'pip'...
    
    1. pip install torch
    2. pip install scikit-learn
    3. pip install numpy
    4. pip install matplotlib
    5. pip install pandas

## Execution
You can directly run the .ipynb file in Jupiter notebook, only after modifying the path of the existing data set in local system and all the requirements being correctly met.

You can also use the weights provided in .pt file , by intialising an instance to class LSTM and accessing the weights to use in different applications as directed in "Loading the weights" cell of the .ipynb file.
## Authors

The code has been solely developed by Souradeep Dutta , an aspiring machine learning enginner and researcher.
Kindly share your feedback and do contribute and suggest for better performance of the model and mutual development 😊.

