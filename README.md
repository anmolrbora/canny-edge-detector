# Canny Edge Detector
Implemented a Canny Edge Detector in Python from scratch to detect edges in a grayscale image. <br>

#### Instructions: <br>

* Run the source code in Jupyter Notebook. <br>
* Make sure the path to the image is correctly set. <br>

#### About:<br>
Canny's Edge Operator consists of four steps;
* Gaussian Smoothing <br>
* Gradient Operation <br>
* Non-maxima suppression <br>
* Thresholding <br>

1. Performed convolution operation by applying 7x7 Gaussian mask to the input image matrix and normalised by dividing all the pixels by the sum of the mask (140). <br>
2. Used Prewitt's operator to compute x and y image gradients from the grayscale image and then computed edge magnitude and gradient angles.<br>
3. Performed Non-Maxima Suppression after getting the normalised gradient angles.<br>
4. Finaly generated a set of binary images by using P-tile thresholding method for P=10%, 30% and 50%.<br>
