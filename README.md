# Machine Learning and Data Mining
## Group 05 - Dog Breed Classification 
**This is the readme.md file for this project. We need to download three file (train.zip - training data, test.zip - test data, model.h5 - model after training).** 

**training data:** *https://drive.google.com/file/d/1Cf2VNB5AlsnAa5kBKcNCkjc-zXHAdzU1/view*. 

**test data:** *https://drive.google.com/file/d/1wU7TWqE05oUEJM1hkegnM6nlE50j6EkY/view?usp=drive_link*.

**Model after training:** *https://drive.google.com/file/d/1n-faJdY8Cuv7wvhwuSIAp9ZD9K4I93M0/edit*.

### Setup before running
After download these file, extra all (include *IT3191E_Group_5.zip*) and then move:
- "training data" and "test data" folder to ".\IT3191E_Group_5\Source Code" folder.
- *model.h5* file to ".\IT3191E_Group_5\Source Code\Demo App".

### Training file:
    - cd .\IT3191E_Group_5\Source Code      <!--make Source Code as the root folder-->
    - pip install -r requirement.txt
**Training file is "Dog-Breed-Classification Group5.ipynb" - a Jupiter file where you can run cell by cell.**

### Run Demo:
    - cd .\IT3191E_Group_5\Source Code\Demo App       <!--make Demo App as the root folder-->
    - python manage.py runserver
    - Now open browser at "http://localhost:8000/", upload image then scroll down to see the predict result
