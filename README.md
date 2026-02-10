# Developing a Neural Network Classification Model

## AIM
To develop a neural network classification model for the given dataset.

## THEORY
An automobile company has plans to enter new markets with their existing products. After intensive market research, they’ve decided that the behavior of the new market is similar to their existing market.

In their existing market, the sales team has classified all customers into 4 segments (A, B, C, D ). Then, they performed segmented outreach and communication for a different segment of customers. This strategy has work exceptionally well for them. They plan to use the same strategy for the new markets.

You are required to help the manager to predict the right group of the new customers.

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 

Write your own steps

### STEP 2: 
Import the necessary Python libraries and load the dataset into the workspace and Perform data preprocessing by handling missing values, encoding categorical variables, and scaling the features.


### STEP 3: 
Split the dataset into training and testing datasets for model evaluation.


### STEP 4: 
Define the neural network architecture with input, hidden, and output layers using PyTorch.


### STEP 5: 
Initialize the loss function and optimizer, then train the neural network using the training dataset.


### STEP 6: 
Evaluate the trained model using test data and compute performance metrics such as accuracy, confusion matrix, and classification report.




## PROGRAM

### Name:Thaanesh V

### Register Number:212223230228

```python
class PeopleClassifier(nn.Module):
    def __init__(self, input_size):
        super(PeopleClassifier, self).__init__()
        #Include your code here



    def forward(self, x):
        #Include your code here
        
# Initialize the Model, Loss Function, and Optimizer

def train_model(model, train_loader, criterion, optimizer, epochs):
    #Include your code here

```

### Dataset Information
<img width="1254" height="241" alt="image" src="https://github.com/user-attachments/assets/9faac321-73c5-4acd-8668-75492cd545ca" />


### OUTPUT
<img width="902" height="345" alt="image" src="https://github.com/user-attachments/assets/5930da1b-808b-41bf-9f0a-e21d5e1e76c6" />


## Confusion Matrix
<img width="772" height="539" alt="image" src="https://github.com/user-attachments/assets/da2324c6-4329-47d8-9869-e0e47aa744a7" />


## Classification Report
<img width="578" height="411" alt="image" src="https://github.com/user-attachments/assets/5cf5c998-6c7c-4df6-948d-6fded16301ec" />


### New Sample Data Prediction
<img width="902" height="345" alt="image" src="https://github.com/user-attachments/assets/5930da1b-808b-41bf-9f0a-e21d5e1e76c6" />

## RESULT
Thus, a neural network Classification model was successfully developed and trained using PyTorch.
