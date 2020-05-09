# django-blog

Steps to run this application on your local system :-
Create virtual enviroment

    `conda create env <enviorment-name>`
    `conda activate <enviorment-name>`
    
Install required libraries

    `conda install -c conda-forge django=2.0.0`
    
Clone the project repo

    `git clone <repo url>`
    
Set the project on local system

     `cd <repo-dir>`
     `python manage.py migrate`
     `python manage.py makemigratons blog`
     `python manage.py migrate`
     `python manage.py runserver`
