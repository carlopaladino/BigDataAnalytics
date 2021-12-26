# BigDataAnalytics 

Big Data Analytics Project

The aim of the project is about predict if an account could potentially do fraudolent or not fraudolent transactions of Ethereum crypto currency.
The fist part is about understanding of the dataset and pre-processing.
Then selection of the most important features for classification and classification itself using different classification models.
Finally explanation of the best classification model with SHAP.

In the end we found that "Total ERC20 tnxs" and "ERC20 most sent token type" are the most important features for the classification.
Their values have a really strong influence with the prediction of the class, especially if the Total ERC20 tnxs is 0 the record will be a non fraud, while if it is 1 or higher it will be a fraud.

