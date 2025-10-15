# Edge-Linking-using-Hough-Transformm
## Name : Mohamed Hameem Sajith J
## reg no: 212223240090
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
<img width="264" height="411" alt="image" src="https://github.com/user-attachments/assets/83e36c2c-fed2-4e66-8302-1ec494822561" />

<img width="264" height="411" alt="image" src="https://github.com/user-attachments/assets/dadef324-ff14-4cf7-a297-d16e58b7a0ac" />


### Canny Edge detector output
<img width="264" height="411" alt="image" src="https://github.com/user-attachments/assets/b6954c41-bb51-468c-bed7-a275d3f128b4" />

### Display the result of Hough transform
<img width="264" height="411" alt="image" src="https://github.com/user-attachments/assets/849a93ea-b82f-4f89-80ca-8d295011c17a" />
