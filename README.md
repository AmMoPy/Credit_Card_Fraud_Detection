# Credit Card Fraud Detection - Regression vs. Ensemble

**How Fraud detection system (FDS) works:**

<img src="https://drive.google.com/uc?id=1vm0zz1duQvQXA7VI6VARjNNkKWSu-WOT" width="800">


FDS consists of many layers four of them are automated, the first two layers are responsible for approving or denying transactions at source; once approved they are sent to additional filtering layers where suspicious ones gets flagged for further inspection by investigators. It’s important to know that approved transactions are already executed, an exchange has already happened, it’s now the responsibility of the additional filtering layers to flag them for damage control.

This notebook discusses predictive modeling for classifying transaction either being fraudulent or not, using a highly imbalanced dataset (< 1% fraudulent transactions); several topics are going to be covered in a 'How Things Works' manner with examples. we'll evaluate different models and assess the impact of introducing some adjustments on prediction results, the following will be covered:

- Principal Components Analysis (PCA)
- How models make predictions, linking visual observations to model behavior on fitted data
- Best metric to use when evaluating models and how some metrics can be misleading
- Assessment of costs associated with prediction errors
- Factors influencing selection of classification thresholds, why optimal thresholds may not be best to use at model deployment
- Threshold moving impact on prediction results and total cost of misclassification errors
- Probability calibration: why and how to?
- Methods for handling class imbalance issue
- Feature importance, intuition vs. model behavior
- Penalized linear models vs. Ensembles

**References:**

This is a minor listing of all the resources that I find really helpful and had significant impact on this project. All of them are invaluable, ordering does not imply favoritism except for StatQuest :D

- **https://statquest.org/**

- https://machinelearningmastery.com/

- https://stackexchange.com/

- https://www.statisticshowto.com/

- https://stats.libretexts.org/Bookshelves/Applied_Statistics

- https://stackoverflow.com/

- http://www.ulb.ac.be/di/map/adalpozz/pdf/Dalpozzolo2015PhD.pdf

- https://www3.nd.edu/~dial/publications/dalpozzolo2015calibrating.pdf

- https://thesai.org/Downloads/Volume11No6/Paper_60-A_Comparison_of_Data_Sampling_Techniques.pdf

- https://www.wiley.com/en-ie/Machine+Learning+in+Python%3A+Essential+Techniques+for+Predictive+Analysis-p-9781119183600

- https://www.udacity.com/course/intro-to-machine-learning--ud120
