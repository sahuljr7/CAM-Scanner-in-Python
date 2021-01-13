# CAM-Scanner-in-Python
The Aim of our Project is:
To create our own Cam Scanner that takes an image as input and then scans the document from the image by applying few image processing techniques and gives the output image with scanned effect. Since the Cam Scanner application being launched in Play Store by China in 2011 that allowed iOS and Android devices to be used as image scanners was banned by the Indian Government for stealing the data of its users. So, we felt the need to target on this project where we can create our own Cam Scanner which does not harm the privacy of its users.

CamScanner-In-Python
Build your own document scanner with OpenCV Python
What is this?
The script takes an image as input and then scans the document from the image by applying few image processing techniques and gives the output image with scanned effect
How does it do this?
Initially we need to resize the images so OpenCV can handle it and then the following functions are applied
1.	Gaussian Blur to smoothen image.
2.	Canny Edges to detect the edges.
3.	Find contours and boundary of the page.
4.	Map the end points of contours to 800 * 800 window.
5.	Apply perspective transform to get scanned or bird eye view of the image.

