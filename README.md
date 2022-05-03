<p align="center">
<a href="https://github.com/Namangarg110/Diagnoze/blob/master/static/images/logo3.png">
	<img src="https://github.com/Namangarg110/Diagnoze/blob/master/static/images/logo3.png" width=20%/>
</a>
	<h2 align="center"> Diagnoze (Disease Detection)</h2>
	<h4 align="center"> Website which detects different disease</h4>
	
</p>


__Web Site__

<img src="https://github.com/Namangarg110/Diagnoze/blob/master/static/images/screen-capture%20(online-video-cutter.com).gif" />


## Functionalities

- [ ]  Detects types of tumor using MRI SCAN 
- [ ]  Detects Covid-19 using X-RAY
- [ ]  Detects chances of heart attack using general health data 
- [ ]  Detects Diabetes using general health data
- [ ]  User Intractive 
- [ ]  User Friendly


## Tech Stack
* Deep Learning:
	-  Tensorflow
	-  Keras
	 
* Machine Learning:
	-  SK-LEARN

* Data Preprocessing:
	-  Pandas
	-  Numpy
	-  Matplotlib
	-  Pickle
	
* Web:
	-  HTML
	-  CSS
	-  JAVASCRIPT
	-  BOOTSTRAP
	-  FLASK

	

## Introduction
We at Diagnoze aim to provide quick results to the problems faced by our clients.Our webapp works on the principle of taking in info regarding the problem and giving instant results which guide them in taking further step towards treatment.Using this process,we have tried to reduce human errors on any ground.We mainly plan to develop a system where the complexity and computation time is low and accuracy is high.

# Working
*Using Deep Learning and web app we have implimented the followings :- 

## Tumor
* We took Images of MRI Scan from the user as input and then using deep learning,we checked for the presence of tumors in the Image.Then according to the result,we have suggested the user to seek professional medical help.
* Model Used :- Convolutional Neural Network
* Accuracy Achieved :-95.34%
* About Model :- The architecture of the NN consists of 6 Convolutional layers and a couple of Dense Layers.The SGD optimizer was used and the loss function used was binary_crossentropy

## Diabetes
* We have used regular health dataset with features like blood pressure,heart rate,age,gender,chest pain etc. to predict if the patient has diabetes or not.
* Model Used:- Dense Neural Network
* Accuracy Achieved :- 97%
* About Model :- The NN consisted of only 3 Dense Layers. Relu and Sigmoid were used as the activation functions.The Adam optimizer was used and the loss function used was binary_crossentropy

## Heart Attack 
* Using regular health data,we predicted if the patient is at the risk of a heart attack.
* Model Used :- SVM Classifier was used
* Accuracy Achieved :- 87%
* About Model :- Using Grid Search the hyperparameters were tuned. Gamma = 1 , C=10


## Corona Virus 
* Taking in the chest x-ray from the patient and considering the general health details,we tried to anticipate if the user has corona virus.

* **Model Used** :- Fine Tuned MobileNet

* **Accuracy Achieved** :- 99.58%

* **About Model** :- The first 23 layers of the mobilenet architecture were frozen and the rest of the layers were trained using the data,The image was preprocessed according to the mobileNet, The Adam optimizer was used and the loss function used was binary_crossentropy



