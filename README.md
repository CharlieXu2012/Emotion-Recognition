# Emotion-Recognition

**Requirements**
1. NodeJs. If you don't have Nodejs installed, install it from [here](https://nodejs.org/)
2. Python (Both the Python 2 as well as Python 3 are supported)

## To start
1. Clone this repo. Change to the newly made directory '`Emotion-Recognition`'
2. Change the working directory to `frontend`
3. Run the command `node server.js`
4. Open your browser and browse to `localhost:3000`
5. Click on `Try out` button
6. The result will be shown on the screen.
7. Click again on the same button to get another prediction.

## Ultimate goal
The project aims to create a webapp that will recognise a person's emotions live in the browser. It can also be further developed to include some nice applications.
## Current status
As of now, the model has been trained from scratch with keras, using TensorFlow backend. The model architecture is shown below.

![alt text](https://github.com/IAmSuyogJadhav/Emotion-Recognition/blob/master/network.png)

## To-Do's
94% accuracy is fine for most purposes, yet it has a lot of room for improvement. Soon going to turn to data augmentation to increase the data avialable for training by performing various modifications on existing data like, rotation, zooming in/out, cropping etc. This prevents overfitting and gives a more reliable model.
The webapp is yet to be implemented. Will be implemented soon.

## Data description
* ```./backend```: Contains the backend part of the project. It contains a file named ```train.ipynb``` that has the code to train this model from scratch, if you wish to. It also contains the images used for training the model ([original source](https://github.com/muxspace/facial_expressions)). Just [clone](https://codeload.github.com/IAmSuyogJadhav/Emotion-Recognition/zip/master) this repository and uncompress the contents and you're ready to go!

* ```./frontend```: Contains the frontend part of the project.

## Contributors
* Backend: [Suyog](https://github.com/IAmSuyogJadhav/)
* Frontend: [Ujjawal](https://github.com/ujjawaljaiswal2017)

## Current Status
* The Webapp works fine on PCs, however you can't currently run it in the browser itself.
* The model is slightly biased currently due to the imbalance of images in the dataset. Will retrain on a sampled dataset once I get over with my exams;)
