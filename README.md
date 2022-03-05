# Text classification for social media comments 
This project uses a cased bert model , tensorflow and is written entirelty in Pytrhon . Its functionality is to classify facebook comments acording to the department it is targetted at .
The steps in conduicting this porject progressed as follows :
  Data collection . Due to the disabling of APIs that could acess facebook data we copy pasted the comments directly from Facebpook and collected over 200 nposts as that was the     quantity available .
  Chosing and implementing the model - We used bert to develope a model for classifying the data . We the n split the testa and training data .
  Training - The model was first tested using 5 epochs and acheived accuracy of 0.4 .The number of epochs were then increased to 10 increasing the accutracy to above 80%.
  Tested - The program was tested witha few comments and it acheived high leveks of accuracy .
  The model was then saved .
How the model works . 
First cell - In the first cell we import import pandas , numpy , tqdm.auto , tensorflow and the bert tokeniser . We then used 
pandas to load the testing data and display it. 
Second cell - The second input cell then displays more information about the data .
The fourth inpot xcell saves the department klabels as integers and then counts the numbeer of departments or classes in the data . 
The fuifth inputr cell loands the bert model then proprocesses the data .
Ceklls 6,7,8and 9 prepare the data then map the labels to the comments and finally converts the data into tokens 
Cell 11 decides the size of the batch while the 12th cell splits the test and training data .
Cell 13 and 14 creates the model then shows us some information about the model created and ready to be trained .
The 16th input cell then trains the model and saves it to a local file .The 19th cell then uses the model to acess the model in order to make a prediction on the coment that the user enters .
