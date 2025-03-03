# Deep fake detection Django Application
## Requirements:

**Note :** Nvidia GPU is mandatory to run the application.
- CUDA version >= 10.0 for GPU
- GPU Compute Capability > 3.0 


You can find the list of requirements in [requirements.txt]
Python >= v3.6
Django >= v3.0
```

# Running application locally on your machine


#### Step 1 : Clone the repo and Navigate to Django Application

`git clone https://github.com/SEELAM-MOUNIKA/deepfake-face.git`

#### Step 2: Create virtualenv (optional)

`python -m venv venv`

#### Step 3: Activate virtualenv (optional)

`venv\Scripts\activate`

#### Step 4: Install requirements

`pip install -r requirements.txt`

#### Step 5: Copy Models

`Copy your trained model to the models folder i.e Django Application/models/`

- You can download our trained models from [Google Drive](https://drive.google.com/file/d/18FT4Q8QGqyAf9hzWF5aZl8Sbgn3WkCuW/view?usp=sharing)

**Note :** The model name must be in specified format only i.e *model_90_acc_20_frames_final_data.pt*. Make sure that no of frames must be mentioned after certain 3 underscores `_` , in the above example the model is for 200 frames.


### Step 6: Run project

`python manage.py runserver`


 
 
