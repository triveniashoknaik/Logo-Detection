# Logo-Detection

1. Developed a software that would identify the brand logo in the probe image and bound it by a rectangular 
box around the recognized logo .
2. Converted the template logo and image containing the same logo into edge images using the sobel operator.
3.Since the image may contain scaled logo template, vary the scale of the logo and match each scaled template 
to the image to get maximum correlation.
4. Return the scaled template for which the correlation coefficient value is maximum.
5. Draw the bounding box around the maximum match location.
6. Tested with 133 images and 80 were identified with correct logo and bounding box around it with an accuracy of 60.15%.
