# Human Activity Recognition using TensorFlow (CNN + LSTM)

Human Activity Recognition example using TensorFlow on Videos using UFC-50 dataset and an LSTM + CNN. Classifying the type of movement amongst the categories which we can choose of our own choice.

## Dataset used:
The dataet used is UFC-50 which contains 50 categories of human activities such as running, walking, swing.
For visualization, we will pick 20 random categories from the dataset and a random video from each selected category and will visualize the first frame of the selected videos with their associated labels written. This way we’ll be able to visualize a subset ( 20 random videos ) of the dataset.

![image-1024x993](https://user-images.githubusercontent.com/75989377/178715402-834b63c4-05df-4cda-b3a0-6c505be02199.png)


## Machine model:
Ther will be convlstm model with a total of 13 layers.
We have Split the Data into Train ( 75% ) and Test Set ( 25% ).

![swing](https://user-images.githubusercontent.com/75989377/178714090-7d0258b6-b2e4-4cfa-a896-f2ce5369dc93.jpg)

## Conclusion:
Visualizing the training and validation loss metrices.

![ac](https://user-images.githubusercontent.com/75989377/178714099-44961798-b9e1-4728-93f3-eb0fcd5d8395.jpg)


