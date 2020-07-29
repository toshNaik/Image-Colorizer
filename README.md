# Image-Colorizer
### Uses autoencoders to colorize a gray image.

For training the images are converted to 'Lab' color space from RGB.
The 'L', which is similar to grayscale of the original image is used as input. and 'ab' spaces are predicted.
The input: 'L' and output: 'ab' are concatenated to obtain Lab image which is converted to RGB and displayed.


Gray             |  Predicted
:-------------------------:|:-------------------------:
![](Gray/image1.png)  |  ![](Predicted/image1.png)
![](Gray/image2.png)  |  ![](Predicted/image2.png)
![](Gray/image3.png)  |  ![](Predicted/image3.png)


Better results could be obtained if trained for longer on a larger dataset
