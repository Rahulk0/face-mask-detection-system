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
This system retrieves an image uploaded extract the faces detected in the image, feed each face into a serialized model `best.pt` which outputs a tuple composed of 3 values. The first value indicates the probability of no mask, the second value is the probability of a correct mask and the last one is the probability of the incorrect mask.
In the output picture, ach face is bordered by the color indicating his situation (No mask, Correct, Incorrect).
This website is built from scratch with HTML and CSS deployed to Flask use your laptop to test.



## 🔑 PEREQUISITES

All the dependencies and required libraries are included in the file **requirements.txt** [See here](https://github.com/memudualimatou/FACE-MASK-DETECTION-WEB-APP-FLASK-PYTHON/blob/main/requirements.txt)


## 🚀 INSTALLATION

Clone the repo\
```$ git clone https://github.com/Rahulk0/face-mask-detection-system.git```


Change your directory to the cloned repo and create a Python virtual environment named 'test'

```$ mkvirtualenv test```


Now, run the following command in your Terminal/Command Prompt to install the libraries required

```$ pip3 install -r r.txt```

To run the flask application

```$ flask --app app run```


## 👏 And it's done!
Feel free to mail me for any doubts/query ✉️ face.detection@gmail.com

##  🤝 Contribution
Feel free to file a new issue with a respective title and description on the this mask detection repository. If you already found a solution to your problem, I would love to review your pull request!

## ❤️ Owner
Made with ❤️ by Vaibhavi Srivastava, Varnika Chauhan, Aakanksha Vats, Pratham Goel



