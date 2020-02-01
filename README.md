# Vehicle Crash Model Predictor Project 
Analyzed and cleaned police reports on vehicle crashes from the Police Department of the Montgomery County, Maryland, available from https://data.world/datagov-us. The data consisted of 100,000 unique samples and it was cleaned using Pandas on Jupyter Notebook, to transform the dataset into a usable form. The factors determining the severity of injuries in the event of a crash including environmental and technological factors such as; vehicle brand, vehicle body type, vehicle year of manufacture, weather conditions, light conditions (time of day), and road surface conditions were extracted and used to develop several predictive models with the sci-kit learn (sklearn) library including; Logistic Regression, Decision Tree Classifier, Random Tree Classifier, and K-Neighbors Classifier.  Since most of the data was in the form of strings, data encoding had to be performed on the necessary features first before models could be developed. The models developed were analyzed for their accuracy of predictions and the most relevant model was the Random Tree Classifier model and it was saved for retrieval. Using the pickle library, the saved model was loaded into a FLASK application built to predict from new data supplied and render the outcome to the HTML front-end user interface. This was an individual project.
