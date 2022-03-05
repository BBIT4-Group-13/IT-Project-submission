# Text classification for social media comments 
The project was done by :
                  Group 13
1.	ELIJAH RINDAU             TU01-BE213-0365/2017
2.	PETER MUTAI KIPKORIR     TU01-BE213-0390/2017
3.	MOSES ODHIAMBO            TU01-BE213-0417/2017
4.	GRACE OGUTU                    TU01-BE213-0415/2017
5.	VALENTINE ATEMA          TU01-BE213-0284/2017.

This project uses a cased Bert model, tensor flow, and is written entirely in Python. Its functionality is to classify Facebook comments according to the department it is targeted at.
The steps in conducting this project progressed as follows:
  Data collection- Due to the disabling of APIs that could access Facebook data, we copy pasted the comments directly from Facebook and collected over 200 posts as that was the quantity available.
  Choosing and implementing the model - We used bert to develop a model for classifying the data. We then split it into the test and training data.
  Training - The model was first tested using 5 epochs and achieved an accuracy of 0.4. The number of epochs were then increased to 10 increasing the accuracy to above 80%.
  Testing - The program was tested with a few comments and it achieved high levels of accuracy.
  The model was then saved.
# How the code works. 
First cell - In the first cell, we import pandas, NumPy tqdm.auto , TensorFlow and the bert tokenizer. We then used pandas to load the testing data and display it. 
Second cell - The second input cell then displays more information about the data.
The fourth input cell saves the department labels as integers and then counts the number of departments or classes in the data. 
The fifth input cell loads the bert model then preprocesses the data.
Cells 6, 7,8 and 9 prepare the data then map the labels to the comments and finally convert the data into tokens 
Cell 11 decides the size of the batch while the 12th cell splits the test and training data.
Cell 13 and 14 creates the model then shows us some information about the model created and ready to be trained.
The 16th input cell then trains the model and saves it to a local file .The 19th cell then uses the model to access the model in order to make a prediction on the comment that the user enters .
Challenges and limitations .
Computer capacity - The machines we had were not esspecially equped for machine learning and developed various problems along the way .
Internet connectivity - The model was running online and required a strong internet connection whcih sometimes failed because of geographical limitations .
