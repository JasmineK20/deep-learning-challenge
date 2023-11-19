# deep-learning-challenge


#### Overview of the Analysis
____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

The purpose of this exercise was to determine if applicants would be successful if funded by Alpahbet Soup, a non-profit organization. Two deep learning models were created based on various features from the applicants.


###### Results 

### Data Preprocessing

What variable(s) are the target(s) for your model?
  * Target variable is "IS_SUCCESSFUL"

What variable(s) are the features for your model?
  * APPLICATION_TYPE—Alphabet Soup application type
    
    AFFILIATION—Affiliated sector of industry
    
    CLASSIFICATION—Government organization classification
    
    USE_CASE—Use case for funding
    
    ORGANIZATION—Organization type
    
    STATUS—Active status
    
    INCOME_AMT—Income classification
    
    SPECIAL_CONSIDERATIONS—Special considerations for application
    
    ASK_AMT—Funding amount requested

What variable(s) should be removed from the input data because they are neither targets nor features?
  * In the optimization model, the "EIN" column was dropped, and the "NAME" column was binned and replaced.

### Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?

Initial Model:
![image](https://github.com/JasmineK20/deep-learning-challenge/assets/135649789/02f6a919-30ad-457e-a0d0-48c67c192bac)

Neurons: 80 (Layer 1) and 30 (Layer 2)
Layers: 2
Activation Function: ReLU for hidden layers and Sigmoid for the output layer






Were you able to achieve the target model performance?


What steps did you take in your attempts to increase model performance?



