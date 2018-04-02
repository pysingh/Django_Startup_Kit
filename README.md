# Django_Startup_Kit

Make sure you've install python verion 3.6

#Run this command to install virtualenv

sudo apt-get install python3-venv

#Create a virtualenv by running below command in the root folder (inside Django_Startup_Kit)

python3.6 -m venv venv

#Activate virtual env

source venv/bin/activate

#Install the requirements

pip install -r requirements.txt

#run migration

python manage.py migrate

#run the server

python manage.py runserver

#open below URL in browser

http://127.0.0.1:8000/