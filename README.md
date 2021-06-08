# Shape-Detector-OpenCV
A program that enables the user to draw shapes, and then identifies whether it's a known shape. It can identify circles, squares, rectangles, triangles, and pentagons. 

A project developed using OpenCV which employs the use of contour detection. The Jupyter Notebook contains preliminary code which shows shape detection on a single sample image. 
The contours of shapes are extracted and stored in a list. Any image containing a shape can then be compared with the existing contours to match it.

The shape_predictor() function contains code to detect contours of any sample image, and draw bounding rectangle on it. 

draw_line() function enables user to draw on a blank screen by checking mouse events.

Once the last cell is executed, press 'c' to clear the screen, 'p' after drawing is complete to predict the shape, and 'e' to exit.
