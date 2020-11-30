# Detecting-Numbers-from-Jersey
In the present day Football operating system , everyone tries to use the power of machine learning as well computer vision to detect the players jersey , player jersey colour , football movement and much more . Many companies already achieved many things like Ball tracking , player detection etc from real time football . In this project i tried to detect the jersey number of  a foot ball player who is playing in the football ground !! That means this AI model will have the power to detect the player / team based on its jersey number.

### How it will work : 

The process how our algorithm works is something like this :

* First Player iamges are annotated from any real time football game , by using any video annotation tool !!

* Next the annotated player image will be passed to the computer vision model that will function to detect the proper edge , colour , carvature , Region of spread & homography of number part and will detect which number it is ? 

* Finally the number will be stored in a file in the operating system.

### Tech Stack used : 
```
1.) Python 
2.) Open CV 
3.) K-nn & K-Means
4.) Mahotas Python Library 
5.) Segmentation techniques
```
### How to Run the script : 

Before knowing how to run the script let us know how our script is working : 
```
Step 1 : First collect and save the data at /Images/.. folder 
Step 2 : Then create a dummy data for numbers values at ../Data/generalsamples.data folder 
Step 3 : Create a Support training library to help in image denoising and deal with hazy images ,
         hence run the script ../support_library.py 
Step 4 : Next train the model K-means for image segmentation and dong homography etc 
         by running the ../training.py
Step 5 : Finally run ../detection_numbers_image.py for final edge detection and having the output
```
Now finally run the script in this manner : 
```
Clone the repo .../ git.clone.../
cd C:// "path of cloned repo "
python detection_numbers_image.py
     input the image number 
     
#### Output #####
```
### Working outputs : 

Output from the command propmt : 

![alt_text](img1.PNG)
