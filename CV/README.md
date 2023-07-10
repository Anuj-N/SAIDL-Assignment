This is my attempt for the CV task. I have tried to attempt this task in the following manner:

First in myClip_csv_generator.ipynb, I did the following steps:
1) Downloaded the dataset
2) Preprocess the dataset using pandas and generate csv files
   
Then in myClip.ipynb, I did the following steps:
1) Generated masks for the dataset using OpenCV
2) Made custom encoder (non-trainable) using CLIP's functions
3) Made custom decoder (trainable)
4) Made Dataloader class and loaded the dataset
5) Implemented the Training Loop
