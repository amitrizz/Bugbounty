# Bugbounty
a event website where user find bug/vulnerabilities in website and get rewards 
steps to upload floder or project to github from terminal

step 1 download from GitHub
git clone or download zip file

step 2 create virtualenv env  and activate

pip install virtualenv

virtualenv envirmentname/Scripts/activate  or try python envirmentname/Scripts/activate

step 3 install all requirements needed in the project

pip install -r .\requirment.txt

step 4 to create database we need run db.create_all() in view.py inside @app.route("/") def function
or we can do like 
flask db init 
flask db migrate
flask db update

step 5 py app.py  run flask app

step 6 deactivate
