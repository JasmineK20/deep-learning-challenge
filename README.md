# deep-learning-challenge


#### Overview of the Analysis
____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

The purpose of this exercise was to determine if applicants would be successful if funded by Alpahbet Soup, a non-profit organization. Two deep learning models were created based on various features from the applicants.


###### Results 

### Data Preprocessing

What variable(s) are the target(s) for your model?
  * Target variable is "IS_SUCCESSFUL"

What variable(s) are the features for your model?
  * APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE,  ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT
       
What variable(s) should be removed from the input data because they are neither targets nor features?
  * In the optimization model, the "EIN" column was dropped, and the "NAME" column was binned and replaced.

### Compiling, Training, and Evaluating the Model

Initial Model:


![image](https://github.com/JasmineK20/deep-learning-challenge/assets/135649789/02f6a919-30ad-457e-a0d0-48c67c192bac)



How many neurons, layers, and activation functions did you select for your neural network model, and why?

* Neurons: 80 (Layer 1) and 30 (Layer 2)

* Layers: 2

* Activation Function: ReLU for hidden layers and Sigmoid for the output layer

Optimization Model: 


![image](https://github.com/JasmineK20/deep-learning-challenge/assets/135649789/25543b18-1537-4e3b-a9ce-e5b37a98088f)


* Neurons:  7 (Layer 1), 14 (Layer 2), and 21 (Layer 3)

* Layers: 3

* Activation Function: ReLU for hidden layers and Sigmoid for the output layer

Were you able to achieve the target model performance?

Initial Model: 

![image](https://github.com/JasmineK20/deep-learning-challenge/assets/135649789/ffb3dc8a-3b34-4efc-8578-a7ee5184e054)

Accuracy: 72.7%

Optimization Model: 

![image](https://github.com/JasmineK20/deep-learning-challenge/assets/135649789/8f1ce78a-eaee-4b9c-9635-dafd0b396f0b)

Accuaracy: Approximately 77.5%


What steps did you take in your attempts to increase model performance?

* Removed EIN and added a third layer 





