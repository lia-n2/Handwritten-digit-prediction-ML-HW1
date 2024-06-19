# Handwritten-digit-prediction-ML-HW1

n this assignment, the objective is to utilize machine-learning models to predict handwritten digits, which were created using a pen stylus by more than 40 different authors.

Datasets:
The x,y position of the pen was recorded eight times, starting with (x1,y1) when the pen first touched the paper, and concluding with (x8,y8) representing the last pen position. For ease of processing, the coordinate system is standardized to range from 0 to 100 for both the x and y dimensions. Utilizing all 8 coordinate pairs overly simplifies the problem, hence, we will opt to utilize positions (x3,y3) through (x6,y6) instead.

In the provided zip file (hw1_upload.zip Download hw1_upload.zip), you'll discover a CSV file (studentsdigits-train.csv) containing the training datasets. Each entry in the dataset comprises positions (x3,y3) through (x6,y6), followed by a digital label (0-9). Additionally, an unlabeled test set (studentsdigits-test.csv) is included. Your objective is to train a multi-class classifier using the training set and subsequently generate predictions on the unlabeled test set.

Both the training and test sets originate from the same data distribution, ensuring no distribution shift in the test set. You have the flexibility to utilize any method of your choice to develop the classifier, as well as any machine learning packages or frameworks.

An IPython notebook (main.ipynb) is also included in the zip file offering a skeleton code that reads the datasets into lists and outputs inference results to upload_predictions.txt. Please begin with this notebook and insert your code for training (including any early stop mechanism, if applicable), and inference.

Question lists:
Q1: Train a machine learning classifier, please specify i) your classification method, and ii) the loss function for multi-class classification.
Q2: Please describe a method to estimate your performance before testing on the test set.
Q3: Please list the key hyperparameter values to consider, e.g., the choice of optimizer (e.g., Adam, SGD), learning rate, batch size, and possibly the architecture of machine learning classifier.
Q4: Please list the key Python packages used in this assignment.
Q5: If applicable, discuss any other methods attempted besides the one submitted, along with their outcomes and reasons for not choosing them.
