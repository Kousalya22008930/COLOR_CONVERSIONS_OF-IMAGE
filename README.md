# COLOR_CONVERSIONS_OF-IMAGE
## AIM
Write a Python program using OpenCV that performs the following tasks:

i) Read and Display an Image.

ii) 	Draw Shapes and Add Text.

iii) Image Color Conversion.

iv) Access and Manipulate Image Pixels.

v) Image Resizing

vi) Image Cropping

vii) Image Flipping

viii)	Write and Save the Modified Image


## Software Required:
Anaconda - Python 3.7
## Algorithm:
### Step1:
Load an image from your local directory and display it.
### Step2:
o	Draw a line from the top-left to the bottom-right of the image.
o	Draw a circle at the center of the image.
o	Draw a rectangle around a specific region of interest in the image.
o	Add the text "OpenCV Drawing" at the top-left corner of the image.

### Step3:
o	Convert the image from RGB to HSV and display it.
o	Convert the image from RGB to GRAY and display it.
o	Convert the image from RGB to YCrCb and display it.
o	Convert the HSV image back to RGB and display it.

### Step4:
o	Access and print the value of the pixel at coordinates (100, 100).
o	Modify the color of the pixel at (200, 200) to white.

### Step5:
o	Resize the original image to half its size and display it.
### Step6:
o	Crop a region of interest (ROI) from the image (e.g., a 100x100 pixel area starting at (50, 50)) and display it.
### Step7:
o	Flip the original image horizontally and display it.
o	Flip the original image vertically and display it.

### Step8:
o	Save the final modified image to your local directory.


##### Program:
### Developed By: KOUSALYA A.
### Register Number: 212222230068

### i)Read and Display an Image
i.Load an image from your local directory and display it.
```
import cv2
image=cv2.imread('naturek.jpg',1)

cv2.imshow('NATUREK',image)
cv2.waitKey(0)
cv2.destroyAllWindows()
```
![image](https://github.com/user-attachments/assets/8cd3bd4a-a1f2-4aab-9413-ddb8972701ec)

### ii)Draw Shapes and Add Text
(1) Draw a line from the top-left to the bottom-right of the image.
```

```
2.Draw a circle at the center of the image.
```

```
3.Draw a rectangle around a specific region of interest in the image.
```

```
4.Add the text "OpenCV Drawing" at the top-left corner of the image.
```

```

### iii)Image Color Conversion
(i)Convert the image from RGB to HSV and display it
```

```
(2) Convert the image from RGB to GRAY and display it.
```

```
(3) Convert the image from RGB to YCrCb and display it.
```

```
(4) Convert the HSV image back to RGB and display it.
```

```

### iv)Access and Manipulate Image Pixels
(1) Access and print the value of the pixel at coordinates (100, 100)

(2) Modify the color of the pixel at (200, 200) to white
```
import cv2
image = cv2.imread('naturek.jpg',1)
image = cv2.resize(image,(400,300))
cv2.imshow('ORIGINAL IMAGE',image)
image[200, 200] = [255, 255, 255] 
cv2.imshow('MODIFIED IMAGE', image)
cv2.waitKey(0)
cv2.destroyAllWindows()
```

### v)Image Resizing
Resize the original image to half its size and display it.
```

```


### vi)Image Cropping
Crop a region of interest (ROI) from the image (e.g., a 100x100 pixel area starting at (50, 50)) and display it.
```

```

### vii)Image Flipping
(1) Flip the original image horizontally and display it.
```

```
(2) Flip the original image vertically and display it.
```

```

### viii)Write and Save the Modified Image
Save the final modified image to your local directory.
```

```


## Result:
Thus the images are read, displayed, and written ,and color conversion was performed  successfully using the python program.







