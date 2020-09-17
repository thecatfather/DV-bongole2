# DV-bongole2

Task1 has been completed while task2 needs a little bit of work.

I have tried 2 methods for Task1:
  1) Utilizes the colorthief library for getting dominant colors. (14/15 blue correct, 13/14 yellow correct)
  2) Uses HSV values and range of blue colors to get mask. (13/15 blue correct, 12/14 yellow correct)
  
To run 1st method of task1
``` 
python KTHFSDV_perception_task1_1.py 
```
To run 2nd method of task1
```
python KTHFSDV_perception_task1_2.py
```

For Task2:

I have used YOLOv4 to train a traffic cone detector in google colab. It detects with a high mAP score of 96-98% but does not classify cone color.
I tried to use this model to train a newer model based on self labelled blue cones and yellow cones (basically tried transfer learning) but it gave poor results.

  -results.avi, results2.avi, results3.avi correspond to the cone object detection without using trying to detect color of the cone. Maybe threshold of cone detection can be       increased. 

  -results1_1.avi and results3_1.avi correspond to (trying to) detect color of cones.

The rule quiz file is FSDV.pdf
