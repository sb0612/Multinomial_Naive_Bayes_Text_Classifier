# Text Classification Using Naive Bayes Classification

### Synopsis
The Naive Bayes Classifier algorithm for Text Classification has been used to create the model. Following are the features of this project - 
  - Pre process the data before entering in to the Naive Bayes Classifier Algorithm. It removes all the stop words and it uses random algorithm to choose 5 classes for training and testing.  
  - The Algorithm will take the created vocabulary.
  - The Program has 2 broad parts - 1 for Training and 1 for Testing to get the accuracy


### Software’s Used
Following are the software’s used to develop this project - 
  - Python 3.6
  - IDE: PyCharm - Community Edition 2017.2

Following are the Python packages used in the code - 
  - isfile
  - join
  - listdir
  - random
  - collections
  - sys
  - logging
  - nltk
  - math

### How to Run the Code 

Following are the steps to run the code - 
  - Download the project folder - "NaiveBayes" and save in the local
  - Start PyCharm
  - Open the project folder selecting the saved project folder.
  - Preprocessing.py script needs 2 inputs from the user: 
    - Train Dataset Path
    - Testing Dataset Path
  - Run the NaiveBayes.py and get the following outputs -
    - Accuracy
    
### Results

We ran the code multiple times (over 100) for 5 news groups chosen randomly from 20 news groups. All the results are independent and different depends on the randomly chosen 5 classes. 

Following is the best result we got :
  - Class Names: ['talk.politics.guns', 'sci.space', 'rec.autos', 'sci.crypt', 'soc.religion.christian'] ,
  - Accuracy : 92.25%

Please see the Log file. 


### References
  - http://nlp.stanford.edu/IR-book/pdf/13bayes.pdf
  - http://www.statsoft.com/textbook/naive-bayes-classifier
  - http://www.inf.ed.ac.uk/teaching/courses/inf2b/learnnotes/inf2b-learn07-notes-nup.pdf