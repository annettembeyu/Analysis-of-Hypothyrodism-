# Analysis-of-Hypothyrodism-for Nairobi-Hospital


## Description
Nairobi Hospital conducted a clinical camp to test for hypothyroidism. The data collected focused on Thyroid patients.The dataset will be used to accomplish the following:  
**Build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.**

The analysis will be approached as follows:

**Approach 1: Decision trees**:
- Make a prediction using decision tree on whether the patient has hypothyroid or not  using at least 2 out of the 3 advanced models namely:
        i. Random forests
       ii. Ada boosted trees
      iii. gradient boosted trees.
- Optimize each of the above models and document how the hyperparameters were set up.
- Identify which of the models I trust most(on the basis of accuracy), and using the model  determine which features are most impactful in influencing the prediction
- Note: Wwith decision trees, a lot of data cleaning is not needed. 


**Approach 2: SVM:**

- With this model, data cleaning is a little bit so as to make sense of the features.

- I will document what transformation I have done on the data.

- I will apply Polynomial, linear and rbf kernel function to build my SVM model and then evaluate their performance and pick the kernel that performs the best. I will tune my parameters to improve the performance of the model and further visualize the models. I will use any two features to build the models for this step.

**Note:** I will use decision trees to obtain the most preferable features. However, these features obtained by decision tree might not be suitable for SVM hence I will graph them first.

-  After getting the  best performing kernel, I will use it together with the tuned parameters and repeat the prediction but this time using additional features. I will then compare the model you've just created with the 2-features version. 
