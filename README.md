# virtual painter
This project is about using openCV and mediapipe libraries   to utilize the webcamera for drawing in real time.   
The main idea is:   
* detect hands using mediapipe
* detect wheither the index and middle fingers are up
* detect fingers' tip location
* draw a line when only the index finger is up and make a sellection when both index and middle fingers are up



# Installation
There are some prerequisites that are needed to be done to be able to run this project.
It's needed to install the required libraries by running the following commend in the project's directory:
```bash
pip install -r requirements
```
now you can run the project directly from your terminal:
```bash
python main.py
```



