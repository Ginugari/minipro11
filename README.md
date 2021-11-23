# minipro11
Colour detection is the process of detecting the name of any colour. Well, for humans this is an extremely easy task but for computers, it is not straightforward. 
Human eyes and brains work together to translate light into colour. Light receptors that are present in our eyes transmit the signal to the brain. Our brain then recognizes the colour. 
Since childhood, we have mapped certain lights with their colour names. 
Coming to computers, We will be using somewhat same strategy for detecting the colour digitally

Colour detection is the process of detecting the name of any colour. Well, for humans this is an extremely easy task but for computers, it is not straightforward. 
Human eyes and brains work together to translate light into colour. Light receptors that are present in our eyes transmit the signal to the brain. Our brain then recognizes the colour. 
Since childhood, we have mapped certain lights with their colour names. 
Coming to computers, We will be using somewhat same strategy for detecting the colour digitally

Before starting with this Python project – Live Colour Detection, you should be a little bit familiar with the computer vision library of Python that is OpenCV and NumPy.
OpenCV, Pandas, and NumPy are the Python libraries that are necessary for this project in Python. I have explained later in this article how to install them

OpenCV (Open-Source Computer Vision Library) is an open-source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products.
By using it, one can process images and videos to identify objects, faces, or even handwriting of a human.

Software Requirements :
Python Idle v 3.2
Windows 7 or higher
RAM 4 GB or higher
Storage of at least 500 MB 

Implementation:
Take the Input image from the user.
Read the Colors CSV file using Pandas.
Set a mouse call back event on a window.
Calculate the RGB values of the double-clicked co-ordinates.
Return the color name of the point using RGB values.
Display the image on the window.
Run the python file.

Calculate Distance using RGB values: 
Now, We have the r, g and b values. We need to get the color name from RGB values. To get the color name, we calculate a distance(d) which tells us how close we are to color and choose the one having minimum distance.

	d = abs(Red – ithRedColor) + abs(Green – ithGreenColor) + abs(Blue – ithBlueColor)
