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





![subhomepage](https://github.com/amitrizz/Bugbounty/assets/74492526/bdf75902-a349-4f50-94df-1438ea0f4fc4)
this is home page of bug bounty submission portal

![admin pannel](https://github.com/amitrizz/Bugbounty/assets/74492526/7a4a72d3-1647-4388-85f3-87a9839771b4)

In the admin panel, we will review all submissions, announcements to all users or specific users, user feedback,
all user admin or player, search by userId



![leaderboard](https://github.com/amitrizz/Bugbounty/assets/74492526/cff2d9a9-3f08-4f95-9789-a304070d3cf0)

here all users scorecard with userID as well as team name, here team name is unique, and the roll no also,
on user can not be part of two teams.


![Submit answer](https://github.com/amitrizz/Bugbounty/assets/74492526/3bac43e5-0df3-46b3-9b3b-eda2fc601c3e)

here user finds bugs and submits what bug he/she finds with an explanation.




