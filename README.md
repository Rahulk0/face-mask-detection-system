<h2 align="center"> FACE MASK DETECTION SYSTEM  </h2>
<br><br>



## 😷 FACE MASK DETECTION  😷

A face mask detection is a system capable of detecting if one or more individuals is/ are wearing their face mask. This project displays the number of faces detected, the number of peaople wearing the face mask **correctly**, **incorrectly** or **not** in a picture. 
With the increasing number of COVID-19 victims, integrating systems capable of detecting people wearing a face mask properly or not will help us track them easily. I please everyone to wear their face mask correctly to reduce the risk of contaminating one another.
<br><br>


## ⚠️ TECHONLOGY USED

* [OPENCV](https://opencv.org/about/)

* [TENSORFLOW](https://www.tensorflow.org/)

* [FLASK](https://en.wikipedia.org/wiki/Flask_(web_framework))

<br><br>

## ⚙️ HOW THE SYSTEM WORKS?

This system is a mask detection project that detects face mask on people'face. This flask web app detects if someone is wearing a face mask correctly, incorrectly or not.
This system retrieves an image uploaded extract the faces detected in the image, feed each face into a yolov5 model weight `best.pt` which outputs a tuple composed of 3 values. The first value indicates the probability of no mask, the second value is the probability of a correct mask and the last one is the probability of the incorrect mask.
In the output picture, ach face is bordered by the color indicating his situation (No mask, Correct, Incorrect).
This website is built from scratch with HTML and CSS deployed to Flask use yourlaptop to test.

<br><br>

##⚡️ How the System Works?
The Face Mask Detection System is a Flask web app that detects face masks on individuals' faces. The system retrieves an uploaded image, extracts the faces detected in the image, and feeds each face into a serialized model mask_detector.h5. The model outputs a tuple containing the probability of no mask, the probability of a correct mask, and the probability of an incorrect mask. Each face in the output image is bordered by a color indicating the situation (No mask, Correct, or Incorrect). The website is built from scratch with HTML and CSS deployed to Flask.
