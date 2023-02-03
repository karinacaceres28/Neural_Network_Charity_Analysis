# Neural_Network_Charity_Analysis


The purpose of this project was to use the knowledge of machine learning and neural networks to help Alphabet Soup, a company wanting to predict whether applicants will be successful by their funding. In doing so, a CSV file was used containing over 34,000 organizations that have received funding from them over the years.

## Results

### Data Processing
1.	The variable considered the target in the module was the “IS_SUCCESSFUL” column.
2.	What variables considered to be the features for the module are the following:
a.	“APPLICATION_TYPE”
b.	“AFFILIATION”
c.	“CLASSIFICATION”
d.	“USE_CASE”
e.	“ORGANIZATION”
f.	“STATUS”
g.	“INCOME_AMT”
h.	“SPECIAL_CONSIDERATION”
i.	“ASK_AMT”
3.	The variables that are neither targets nor features and removed from the input data were the “EIN” and “NAME” columns.

### Compiling, Training, and Evaluation the Model

#### Attempt 1
<img width="873" alt="Attempt 1" src="https://user-images.githubusercontent.com/110318652/216480506-317426bd-812e-4b92-be43-0609334e48d1.png">

<img width="587" alt="Attempt 1 percentage" src="https://user-images.githubusercontent.com/110318652/216480518-99943f6b-e706-4d89-92ab-20786a1f26c2.png">

First Attempt: I had 80 neurons on the first hidden layer and 30 on my second layer. Both first and second hidden layers have the activation function as “RELU.” The output layer had the activation function as “SIGMOID.” This outputs a 68% accuracy.

#### Attempt 2
<img width="861" alt="Attempt 2" src="https://user-images.githubusercontent.com/110318652/216480542-d6d681b1-f63f-4a6d-ab6e-7063e1480be5.png">

<img width="577" alt="Attempt 2 percentage" src="https://user-images.githubusercontent.com/110318652/216480559-c8cf3817-e020-4dad-9c8a-7f054fa9cd88.png">

Second Attempt: I had 90 neurons on the first hidden layer and 30 on my second layer. Both first and second hidden layers have the activation function as “RELU.” The output layer had the activation function as “SIGMOID.” The outputs a 59% accuracy.


#### Attempt 3
<img width="864" alt="Attempt 3" src="https://user-images.githubusercontent.com/110318652/216480573-1fc4f0c9-94f5-44bc-9a55-d3f80e277593.png">

<img width="575" alt="Screenshot 2023-02-02 at 8 44 41 PM" src="https://user-images.githubusercontent.com/110318652/216492193-051e4444-1fb9-4a01-b2a8-19464924d6b9.png">

Third Attempt: I had 70 neurons on the first hidden layer and 30 on my second layer. Both first and second hidden layers have the activation function as “RELU.” The output layer had the activation function as “SIGMOID.” This outputs a 69% accuracy.

## Summary
Based on the results, I was unable to reach higher than 69% accuracy. The only thing I changed in my attempts was my first hidden layer. 
