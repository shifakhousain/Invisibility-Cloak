# Invisibility-Cloak
This project demonstrates a basic implementation of a "Cloak effect" using OpenCV and python 
The program is set in such a way that at first, it capture's a screen /pic from camera and then using color detection technique, it detects Blue Color and makes it transparent or replaces with the previous screen. 
The Program works by identifying the different colors and shades of blue green color, this then after detecting it becomes Invisible. 
In short 
The program starts by Importing CV2 and Numpy packages.
•	I prefer using pycham 
Minimize image
Edit image
Delete image

pycham
•	Next selection of camera where , it captures an image first from your laptop , camera as (0)
•	Creation of Trackbars 
•	These are used to detect various colors from the program 
•	There are named as HSV to make the color detection 
•	Now first initial background is captured using while conidiation
•	This loop waits for 1 sec to allow the camera to stabilize and then captures a frame which will be used as the background. The loop continues until a valid frame is obtained 
•	It detects blue color 
•	Once the blue color is detected the image then puts a mask over it as a transparent object using BGR color pattern 
Now lets summarize the entire program 
Its a fun way of understanding programming and learn the machine learning methods of computer vision 
•	Initializes the camera and track bars 
•	Captures a reference background frame 
•	Continuously captures live video frame 
•	converts each frame to HSV color space and creates a mask for a specific color range 
•	Processes the mask to remove noise and enlarge it 
•	Combines the processed frame with the background to create the visual effect of the cloak diapering
•	Display the result and allow real-time adjustment of color ranges via trackbars 
•	Cleans up resources when finished 
•	Trackbars in OpenCV are interactive slides that let you adjust parameters in real-time, which is useful for tasks like tuning color thresholds. 
•	In this code , they are used to dynamically adjust the HSV thresholds for detecting the color of the cloak, allowing you to fine-tune the color detection interactivity. 

Thankyou for your valuable time , hope this article was informative to learn computer vision in a fun way :) 
Thankyou once again 

