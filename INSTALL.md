# Installation Guide

###### Go to code directory
    cd <dir of classpic-django>
    
###### Enable virtual environment
    pipenv shell
###### Install dependencies
    sudo apt install libpq-dev python3-dev
    pip install -r requirements.txt
###### Migrate database
    python manage.py migrate
###### Run server
    python manage.py runserver
    
###### Create user to access ClassPic. Enjoy!
