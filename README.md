# Weapon-detector-YOLOv9
I developed a CNN for image classification of "One Piece" characters. 
In this work i used the lighting module to give the code a compact and easy to read look, getting a final accuracy of over 98%, working with of over 3500 images.
I belive I could squeeze out some additional accuracy points by training the model for more time, but since I used google colab's GPU I couldn't go over 80 training epochs.

Here you can find:
- [My Python code](https://github.com/ANDREAaNAPPI/One-Piece-CNN/blob/main/One%20Piece%20CNN.ipynb)
- [The data I worked with](https://www.kaggle.com/datasets/ibrahimserouis99/one-piece-image-classifier) Note that This is the original dataset, counting over 11k imgaes, and does include some transformations. In my code I cleaned this data to keep only original images.

I saved the two best performing models according to highest validation accuracy and lowest validation loss, but i couln't upload them here because they are too heavy.


  
![image](https://github.com/ANDREAaNAPPI/Werhouse-of-stuff/blob/main/OP_crew.jpeg)
