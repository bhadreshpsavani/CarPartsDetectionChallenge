# CarPartsDetectionChallenge: Inference
In this step, we test our detector on cat and dog images and videos located in [`CarPartsDetectionChallenge/Data/Source_Images/Test_Images`](/Data/Source_Images/Test_Images). If you like to test the detector on your own images or videos, place them in the [`Test_Images`](/Data/Source_Images/Test_Images) folder. 

## Testing Your Detector
To detect objects run the detector script from within the [`CarPartsDetectionChallenge/3_Inference`](/3_Inference/) directory:.
```
python Detector.py
```
The outputs are saved to [`CarPartsDetectionChallenge/Data/Source_Images/Test_Image_Detection_Results`](/Data/Source_Images/Test_Image_Detection_Results). The outputs include the original images with bounding boxes and confidence scores as well as a file called [`Detection_Results.csv`](/Data/Source_Images/Test_Image_Detection_Results/Detection_Results.csv) containing the image file paths and the bounding box coordinates. For videos, the output files are videos with bounding boxes and confidence scores. To list available command line options run `python Detector.py -h`.

### Input and Output: ###

<img src="/Utils/Images/00229.jpg" width="425"/> <img src="/Utils/Images/00229_car_.jpg" width="425"/> 
<img src="/Utils/Images/00227.jpg" width="425"/> <img src="/Utils/Images/00227_car_.jpg" width="425"/> 
<img src="/Utils/Images/00230.jpg" width="425"/> <img src="/Utils/Images/00230_car_.jpg" width="425"/> 

### That's all!
Congratulations on building Car Part Detector using YOLOv3.

I hope you enjoyed this tutorial and I hope it helped you get our own computer vision project off the ground:

- Please **star** ⭐ this repo to get notifications on future improvements and
- Please **fork** 🍴 this repo if you like to use it as part of your own project.
