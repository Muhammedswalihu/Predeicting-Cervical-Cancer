# Predeicting-Cervical-Cancer


In this project, I developed and trained an XG-Boost classifier to predict the risk of cervical cancer in individuals. The dataset used in this study was obtained from 858 patients at the 'Hospital Universitario de Caracas' in Caracas, Venezuela. The dataset consisted of various features including the number of pregnancies, smoking habits, history of sexually transmitted diseases (STDs), demographic information, and past medical records.

To begin the analysis, I performed Exploratory Data Analysis (EDA) and Data Visualization on the training dataset. This involved examining the distribution and relationships between different variables in the dataset to gain insights into the data.

Next, I prepared the data for model training by performing necessary preprocessing steps such as handling missing values, encoding categorical variables, and scaling numerical features. After preparing the data, I split it into training and test datasets using a suitable ratio to ensure robust evaluation of the model.

The XG-Boost algorithm was then trained on the prepared training dataset using the scikit-learn library in Python. This powerful algorithm is known for its effectiveness in handling complex datasets and producing accurate predictions. During the training process, the model learned patterns and relationships within the data to make predictions about the risk of cervical cancer.

To assess the performance of the trained model, I evaluated its accuracy on both the training and test datasets. The accuracy of the model was found to be -99.562% on the training dataset and -95.348% on the test dataset. These accuracy values indicate the percentage of correctly predicted instances by the model.

Overall, this project successfully applied the XG-Boost algorithm to predict the risk of cervical cancer based on various patient attributes. The achieved accuracy scores demonstrate the effectiveness of the developed machine learning model in accurately classifying individuals and potentially aiding in early detection and prevention of cervical cancer.
