# Weapon-detector-YOLOv9
Using the YOLOv9 architecture I trained a model to detect guns and knives. 
The training of the model has been split in 4 stages because of GPU issues. 
If you are looking for the YOlov9 Github repository, you can find it [here](https://github.com/WongKinYiu/yolov9).

Here you can find:
- [My Python code](https://github.com/ANDREAaNAPPI/Weapon-detector-YOLOv9/blob/main/Guns_%26_Knives_Yolov9.ipynb)
- [The data I worked with](https://www.kaggle.com/datasets/iqmansingh/guns-knives-object-detection) 

I couln't upload The weights of the ultimate model here because they are too heavy.


## Model test: 
### Gun detection (from the movie "Joker"):
![image](https://github.com/ANDREAaNAPPI/Werhouse-of-stuff/blob/main/Joker_shooting.png)
### Knife detection (from the movie "The dark knight"):
![image](https://github.com/ANDREAaNAPPI/Werhouse-of-stuff/blob/main/Joker_knife.png)

These 2 frames are taken from 5s videos on which I tested the model. You can find the full videos [here](https://github.com/ANDREAaNAPPI/Weapon-detector-YOLOv9/tree/main/test_videos).
