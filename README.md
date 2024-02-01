# NuFit - Machine Learning Backend by Quang Nguyen (Completed)

**Overview:**
  + This repo is a small demo Computer Vision app deployed an AI/ML model to detect different kind of food. This repo is a subsystem/backend of [NuFit](https://github.com/qu-ngx/DeFat)
  + The implementations took an average of 180 hours of testing different approaches to complete the first full deployment on Flutter.
  + **Machine Learning Model:** ```SSD-MobileNet-V2-300x300``` (Also work with ```SSD-MobileNet-V2-FPN-Lite-320x320```)
  + **Method of training:** Transfer Learning on trained model with ```COCO2017``` set.
  + **Input/Output layer:** [Kaggle](https://www.kaggle.com/models/tensorflow/ssd-mobilenet-v2/frameworks/tensorFlow2)
  
**Folder Structures:**

  + There are 3 main folders here with ```backend``` and ```object_detection_ssd_mobilenet``` being the main components.
  + [backend](https://github.com/qu-ngx/defat-ml/tree/main/backend) included Jupyter notebook to help training and setting up an online virtual env without having to install locally on personal laptop and computers, labelimg for image labelling, and model quantizer for tflite file size reduction (32 bit down to 8 bit)
  + [object_detection_ssd_mobilenet](https://github.com/qu-ngx/defat-ml/tree/main/object_detection_ssd_mobilenet) - The main app running AI/ML or Food Detection (See the image Demo below)
  + There are indepth uses and documentations inside the codes for easy run.
  + For guide to install ```labelimg```: [labelimg](https://github.com/HumanSignal/labelImg)

**How does it work?**

  + Since this is a completed seperate part, this part alone can be run independently as an app.
  + There are ```8``` types of food that this AI/ML model can detect: french_fries
   ```
    sausage
    grilled_chicken
    fish
    scrambled_egg
    pasta
    lettuce
    cantaloupe
   ```
  + Trained ML model can detect 8 types of food above

**Demo & Run App Demo:**
- Installation guide & Run Guide: [Coming Soon]

**Machine Learning App Demo:**
- **For custom deployment or other model deployment:** Please refer to [flutter-tflite](https://github.com/tensorflow/flutter-tflite)
  
<img width="1280" alt="image" src="https://github.com/qu-ngx/defat-ml/assets/91497379/a7be5a22-4bd4-44c5-832a-9c09aa3ed97b">



