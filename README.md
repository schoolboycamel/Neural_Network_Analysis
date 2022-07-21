# Neural_Network_Analysis

# Overview 

The purpose of this analysis is to implemnent Neural Networks and Deep Learning models using 'TensorFlow' as well as 'Pandas' libraries in Python in order to preprocess datasets and create a 'predictive binary classifier'.

AlphabetSoup, a philanthropic foundation which donates millions of dollars to different organizations is requesting us to implement a data-driven solution which predicts which organizations are worth donating to, and which organizations are high risk, as in the past, many organizations have dissapeared with the cash. In order to accomplish this task, we will create a predictive binary classifier  which will predict which organizations are worth donating to and which are not.

## Resources 

 - Software:
  - Python 
  - Scikit-learn
  - Pandas
  - TensorFlow
  - Keras 
  - Jupyter Notebook
  
## Results

- Data Source:
  -  [`charity_data.csv`](Resources/charity_data.csv)
  
### Data Preprocessing 
- Target Variable: IS_SUCCESSFUL Column
- Dropped Variables:  'EIN' and 'NAME' Columns

### Compiling, Training and Evaluating the Model

Seleceted two hidden layers. 
- First layer: 80 neurons 
- Second layer: 30 neurons

![Pic 1](https://github.com/schoolboycamel/Neural_Network_Analysis/blob/main/Images/Original_layers.png)

Target Score: 75%
Accuracy Score: 73%

![Pic 2](https://github.com/schoolboycamel/Neural_Network_Analysis/blob/main/Images/Original_score.png)

## Attemps taken to increase the model's performance

First attempt: Changed the number of neurons for hidden layers:
  - First layer: 60 neurons
  - Second layer: 30 neurons

![Pic 3](https://github.com/schoolboycamel/Neural_Network_Analysis/blob/main/Images/Optimization_layers.png)

Target Score: 75%
Accuracy Score: 73%

Second attempt: Binned the 'STATUS' column and changed epochs to 50
![Pic 4](https://github.com/schoolboycamel/Neural_Network_Analysis/blob/main/Images/Optimization1.png)

Target Score: 75%
Accuracy Score: 73%

Third attempt: Changed epochs to 150
![Pic 5](https://github.com/schoolboycamel/Neural_Network_Analysis/blob/main/Images/Optimization_2.png)

Target Score: 75%
Accuracy Score: 73%





  
