# :pushpin: Deep Learning Basics : CNN & LSTM


Exploring the basics of deep learning like different types of intialisations, regularizers, dropouts, metrics and preprocessing steps by coding the Convolutional Neural Network (CNN) and Long Short-Term Memory (LSTM) models.

The exercise comprises of two questions, one in which we need to build a CNN model and the other one in which we build a LSTM model for image and text classifications tasks respectively.


## Requirements

:package: PyTorch

Pre-processing <br>
:package: sklearn <br>
:package: nltk <br>
:package: cv2 <br>

Visualizations <br>
:package: matplotlib <br>
:package: wordcloud

## Files
* 'Report.pdf': Contains the complete report for exercise.<br>
* 'code.ipynb' : Contains the complete code for exercise.<br>
* [dataset and saved models](https://drive.google.com/drive/folders/1P0HPlP7oH_uMG5q0WVtIhbT29nO3PiE0) : image data may be NA, few changes need to be made to adapt it some other classification tasks

## Learnings

These findings are based on the experiments performed and may vary in different tasks.

Image classification task was implemented using CNN model exploring 
* he, zero and random intializers techniques - he intializer performed best
* effect of dropouts layer after convo and dense layers - better test accuracy after dense layer
* l1 vs l2 regularizer - l2 regularizer works slightly better than l1 

Text classification task was implemented using LSTM model exploring different number of occurences context, analysing the model using through accuracy and f1 score plots. More previous context helps in achieving better metric values. 


More detailed analysis can be found in the Report.pdf

## Acknowledgments
This exercise was a part of my CSES641 Deep learning course.

:star: Have you found this repository helpful? Give it a star to show your support! :star:
