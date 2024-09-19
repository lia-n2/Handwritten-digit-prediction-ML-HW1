# Handwritten-digit-prediction-ML-HW1

The objective is to utilize machine-learning models to predict handwritten digits, which were created using a pen stylus by more than 40 different authors.

Datasets:
The x,y position of the pen was recorded eight times, starting with (x1,y1) when the pen first touched the paper, and concluding with (x8,y8) representing the last pen position. For ease of processing, the coordinate system is standardized to range from 0 to 100 for both the x and y dimensions. Utilizing all 8 coordinate pairs overly simplifies the problem, hence, we will opt to utilize positions (x3,y3) through (x6,y6) instead.

Both the training and test sets originate from the same data distribution, ensuring no distribution shift in the test set. 
