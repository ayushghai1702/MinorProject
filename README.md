# MinorProject

Hey guys this is our minor project.. First of all let me make clear to all of you that we will fork each other's repository from here.


HOW TO CLONE PROJECT:
      There are two methods:
           1. Download the Zip file and from repository.
           2. type the command given below in the git bash:
                    git clone 'repository complete url'
                    
NOW, HOW TO RUN THE CLONNED DJANGO PROJECT:
      1. Python must be installed and prefer version 3.5. I think all of us should use same version.
      2. setup virtual environment.
      3. Activate the recently made virtual environment and navigate to project directory.
      4. Install the requirements for the project... Just type the command given below.
               pip install -r requirements.txt
      5. Make the migrations
               python manage.py migrate
      6. Create a super user:
               python manage.py createsuperuser
      7. To run the project:
               python manage.py runserver
               
