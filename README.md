# Concrete_data_analysis
**This repository aims to use different machine learning algorithms, optimization techniques, and visualization to make the most reliable predictions on concrete data and analyze it.**



This repository contains various components for concrete data analysis using machine learning. The **DATA** folder holds the dataset used for training and evaluation. Hyperparameter tuning is performed using **OPTUNA** to optimize the model's performance. Additionally, the Probabilistic approach is explored to enhance predictivity accuracy. The project aims to apply different machine learning algorithm techniques to derive meaningful insights from the data.

* **Hyperparameter Tuning**

[Hyperparameter_tuning.ipynb](Hyperparameter_Tuning/Hyperparameter_tuning.ipynb): In this, we are using several optimisation techniques like RandomGrid, Grid SearchCv, Bayesian optimisation, and several optuna-based 
                                                                                 optimisation to get the best model for our data and storing the output from the best model in each optimisation technique in corresponding 
                                                                                  Excel files.
                                                                                                                     
                                                                                                                     
* **Hyperparameter Tuning using OPTUNA**

[Hyperparameter_tuning_Optuna_1.ipynb](Optuna_1/Hyperparameter_tuning_Optuna_1.ipynb): In this, we use different samplers and  prunners present in optuna so that we can have the best result in output for each machine 
                                                                                       learning algorithm  and save the results in the corresponding Excel file.
                                                                                                                                                                  
[Hyperparameter_tuning_Optuna_2.ipynb](Optuna_2/Hyperparameter_tuning_Optuna_2.ipynb): 


* **Model Explanations**

 [Model_explanations_ipynb](Model_Explanations/Model_explanations_ipynb): In this, we have used lime and shap to explain the importance of each feature in determining the resulting outcome of different machine 
                                                                          learning models and explained the consequent output in an interactive visual representation.



 * **Probability Distribution**

 [Probabilistic_Distributions.ipynb](Probabilistic_Distribution/Probabilistic_Distributions.ipynb): In this, we have applied probabilistic distribution over NGB 
                                                                                                   regressor and the Probabilistic Gradient Boosting model to 
                                                                                                   give a coverage of 95% using mean and standard deviation, and 
                                                                                                   the output result is stored in the corresponding Excel file.


 * **Uncertainty Analysis**

 [Uncertainity_analysis_1.ipynb](Uncertainity_Analysis/Uncertainity_analysis_1.ipynb):  In this, we have applied uncertainty analysis to the autosampler in optuna with various prunner to get the best output for 
                                                                                        different models and hypertuned them for best parameters, after that, we have tried to increae the  coverage interval  by using 
                                                                                        conformal prediction, weighted average, puncc,  and mapie to increase the  Reliability of our output data on different machine 
                                                                                        learning models and  making coverage value of nearly 90% interval, and the output for different data are displayed on the 
                                                                                        corresponding model Excel inside [output](Analysis_1/output).
                                                                                        .
                                                                                       


 [Uncertainity_analysis_2.ipynb](Uncertainity_Analysis/Uncertainity_analysis_2.ipynb): In this, we have further extended the concept of 
                                                                                       [Uncertainity_analysis_1.ipynb](Uncertainity_Analysis/Uncertainity_analysis_1.ipynb)                                   to machine learning algorithms of **HistGradient Boosting** and **PGBM** 
                                                                                        model and corresponding outputs are stored in an Excel file in 
                                                                                        [output](Analysis_2/output).
 


                                                                                                         


