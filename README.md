# Card-Tampering Detection
The purpose of this project is to detect tampering of PAN card using computer vision. This project will help different organization in detecting whether the Id i.e. the PAN card provided to them by thier employees or customers or anyone is original or not.

For this project we will calculate structural similarity of original PAN card and the PAN card uploaded by user.

## Summary 
* Finding out structural similarity of the images helped us in finding the difference or similarity in the shape of the images. Similarly, finding out the threshold and contours based on those threshold for the images converted into grayscale binary also helped us in shape analysis and recognition. 
* As, our SSIM is ~31.2% we can say that the image user provided is fake or tampered.
* Finally we visualized the differences and similarities between the images using by displaying the images with contours, difference and threshold.  
