# Alphabet Soup Startup Lending

Venture capital firm Alphabet Soup, is attempting to leverage machine learning and neural networks to create a successful business model to determine the likely hood of business success. The neural network model will take input customer data and determine if a business will be successfull. 


# Technologies:
The program is written using Jupyter notebooks, for ease of code reading and code execution via code blocks. The program lays out a step-wise reporting and program execution. The code is run in a (apidev) environment with the use of the following libraries:

Pandas
Pathlib
tensorflow
Keras
sklearn

# Installation Guide:
Python 3.7.11 - base installation is required. PIP install jupyterlab and required liberaies. 

# Usage:
Program ingests csv data file with customer data. It then create a sequentional model. Data is split into training and testing data sets and standardized. A binary classification model using a neural network is created. Three models are compiled. One as the original with a standard recommended setup and two alternative models with difference in neural layers, nodes and the number of training epochs.

Results were follows:

![original_model_results](https://user-images.githubusercontent.com/95830866/160293756-c9755379-953f-476a-9786-3dc0b11015b2.PNG)

![alternate_1_model_results](https://user-images.githubusercontent.com/95830866/160293759-f4b9d006-0060-4b20-a197-d402fa5d0248.PNG)

![alternate_2_model_results](https://user-images.githubusercontent.com/95830866/160293768-78417744-81b5-435d-8c0e-5f40b1420d5a.PNG)

# Contributors:
This program was developed with base code developed by the Rice-boot-camp. Code was created and added by JPinglia.

# License:
License for this project and associated file is public.
