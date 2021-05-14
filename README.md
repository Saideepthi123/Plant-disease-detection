# Plant-disease-detection

## About the Project
An application that for farmers to detect the type of plant or crops, detect any kind of diseases in them. The app sends the image of the plant to the server where it is analysed using CNN classifier model. Once detected, the disease and its solutions are displayed to the user

## Model

Trained to identify 5 classes for **Disease Detection** and 24 classes for **Disease Classification**

           - Disease Classification Classes

                       - Apple___Apple_scab
                       - Apple___Black_rot
			   - Apple___Cedar_apple_rust
			   - Apple___healthy
			   - Blueberry___healthy
			   - Cherry___healthy
			   - Cherry___Powdery_mildew
			   - Grape___Black_rot
			   - Grape___Esca_Black_Measles
			   - Grape___healthy
			   - Grape___Leaf_blight_Isariopsis_Leaf_Spot
			   - Orange___Haunglongbing
			   - Peach___Bacterial_spot
			   - Peach___healthy
			   - Pepper,_bell___Bacterial_spot
			   - Pepper,_bell___healthy
			   - Potato___Early_blight
			   - Potato___healthy
			   - Raspberry___healthy
			   - Soybean___healthy
			   - Squash___Powdery_mildew
			   - Strawberry___healthy
			   - Strawberry___Leaf_scorch
			
            - Disease Detection Classes
            
			   - Cherry___healthy
			   - Cherry___Powdery_mildew
			   - Grape___Black_rot
			   - Grape___Esca_Black_Measles
			   - Grape___healthy
			   - Grape___Leaf_blight_Isariopsis_Leaf_Spot 
---
## Cloning the project  
* Run command `git clone "https://github.com/Saideepthi123/Plant-disease-detection.git"` and change into the project folder
* Create a virtual environment `env` in the repository (use virtualenv, etc)
*  Activate virtual environment
* Install the requirements


To create virtual environment and install requirements run following commands
```shell script
virtualenv env
```

To activate the environment use following commands:
Window: 
```shell script
.\env\Scripts\activate
```
Ubuntu/Linux
```shell script
source env/bin/activate
```
pip install -r requirements.txt

Command to run the app
---
 - streamlit run app.py

## Demo

- About
	![1](https://user-images.githubusercontent.com/52497119/118314433-c2ab2680-b511-11eb-9a79-e9b48df75692.PNG)
