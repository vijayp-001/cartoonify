# CARTOONIFY

Cartoonify Reality is an OpenCV project that uses core OpenCV functions and the K-Means clustering algorithm to perform image processing and cartoony them. This project shows how good image processing can be used to do the same task that normally takes a machine learning model and high computational power. Usually, the same task is done using either auto-encoders or GANs(Generative Adversarial Networks).

# WORKFLOW

Give images as input.Take the source image, blur it using a Bilateral filter. Use canny to finds its edges. Then convert the image into HSV(Hue-Saturation-Value) format and apply K-means clustering to it. Convert it back to RGB(Red-Green-blue) format and draw contours on the image. Finally, use erosion to thicken the boundaries and display the output image.

# CONTENT USED IN THIS PROJECT 
 computer vision,
 opencv,
 Blurring,
 Canny Edge Detection,
 KMeans clustering,
 Contours,
 Erosion
