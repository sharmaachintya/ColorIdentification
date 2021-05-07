# ColorIdentification

In the given code, I have used opencv, numpy and matplotlib libraries to identify a particular color from an image. It is simple first we will reasd the image and by default image in python are in BGR format so we will convert the image into RGB format and after that we will convert the RGB image into HSV. Then we will define the lower and upper HSV values of that particular color which we want to identify and then we pass the HSV image, Lower HSV value and Upper HSV values of that particular color in a mask and at last with the help of bitwise and we will remove the mask so that we can see only the color which we want to. 

I've also attached a notepad file in which there are HSV values of many colors so that you can use them in any other input image.
