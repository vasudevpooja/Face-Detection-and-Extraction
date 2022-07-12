# Face Detection and Extraction done using CNN YOLOv3 Model.

![Account ownership flow](https://user-images.githubusercontent.com/76071184/178530738-84a1a4af-208e-4197-9b49-51fd47ee7e79.png)

## Process of the Code:

1.	Video converted into Frames (Will act as the Input Image),
2.	YOLOv3 Model used for Face Extraction,
3.	[Pre-trained Model](https://drive.google.com/file/d/1nwe5bzDUe2apKzdyGzXND9b8vI8uh5cT/view?usp=sharing) Used (Used a pre-trained model because a custom model would take a lot of time. Tried creating a custom model training dataset for 4 Images),
4.	Face Detected and Score Displayed,
5.	Gaussian Blur applied to the Image to Remove the Background, only face is retained
6.	Face Extracted and Saved.

## Improvements which can be done:

1.	Optimise the speed. (Takes approximately 15 seconds to detect and extract face as of now)
2.	Detects multiple people but can only extract one face at a time from an image


