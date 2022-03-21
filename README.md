# Neural_Network_Charity_Analysis
Mod 19 Challenge 

## Overveiw 
By using neural networks we were hoping to make a binary classifier that would help Alphabet Soup predict what applicants are worthy of being funded. 

## Results 

### Target
* IS_SUCCESSFUL

### Features 
* APPLICATION_TYPE
* AFFILIATION
* CLASSIFICATION
* ORGANIZATION
* STATUS
* INCOME_AMT
* SPECIAL_CONSIDERATIONS
* ASK_AMT
* IS_SUCCESSFUL

### Variables Removed 
* EIN
* NAME
* USE_CASE

### Compiling, Training and Evaluating the Model
For the neural network I had 80 neurons in the first layer, and 30 in the second. The first and second layers have relu activation functions and and the output layer had a sigmoid. 
![](Resources/Results%231.png)

Unfortunaely the model was not able to acheive the target model preformance of 75%. My accuracy was 64%. 

The steps I took to try and improve my models preformance was to remove additional features, specifically USE_CASE. Then to add additional neurons and additional layers, then finally I changed the activation function of the output layer to tanh. 

## Summary 
Overall my deep learning model did not preform well compared to the goal preformance of 75%. I do think that adding data would help increase accuracy. I would recomend a random forecast classifier as the next model because our data also had some outliers. Ideally more data in a random forecast classifer would be a great scenario to try next.  


