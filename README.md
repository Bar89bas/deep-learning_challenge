Overview:
In this project with the knowledge of Python and Neural Networks Machine learning techniques a model has been built to train and evaluate the applicants who will be successful if funded by the nonprofit foundation Alphabet Soup. In order to identify successful and unsuccessful applicant, we have received csv from Alphabet foundation containing more than 34000 organisations that have received funding from Alphabet Soup.

Scope: 
While building the model we have used panda to manipulate and analysis the data, numpy form Python to create array, Sklearn metrics from Python to split the data into train, test; standardscaler to scale the data and tensorflow to build a model.
Tasks Performed:

Preprocess the Data

Read the charity data csv to a Pandas DataFrame. 
Drop the EIN and NAME columns
Cutoff point to bin rare categorical variables together in a other
Encode categorical variables to dummies with function pd.get_dummies.
Split the preprocessed data into input and target feature. 
Scale the training and testing then using the transform function.

Compile, Train, Evaluate the Data
Setting up model instance and number of input features nodes for each layer using TensorFlow and Keras. 
Assign hidden layer along with output layer with number of nodes and activation function. 

Compile and train model
Evaluate the accuracy of the model.
Export model in HDF5 file. 

Optimise the Model
2 more models are built with 3 different hidden nodes and activation function in order to improve the model3 accuracy and have export it to HDF5 file.
