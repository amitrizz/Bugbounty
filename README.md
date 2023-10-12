# Bugbounty
an event website where users find bug/vulnerabilities in the website and get rewards 
steps to upload folder or project to GitHub from the terminal

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



<h1>This is submission portal</h1>
<br>
<br>
<h3> This is the home page of the bug bounty submission portal</h3>

![subhomepage](https://github.com/amitrizz/Bugbounty/assets/74492526/bdf75902-a349-4f50-94df-1438ea0f4fc4)


<br><br>
<h3>In the admin panel, we will review all submissions, announcements to all users or specific users, user feedback,
all user admin or player, search by userId</h3>


![admin pannel](https://github.com/amitrizz/Bugbounty/assets/74492526/7a4a72d3-1647-4388-85f3-87a9839771b4)


<br><br>
<h3> Here all users' scorecards with userID as well as team name, here team name is unique, and the roll no also,
on user can not be part of two teams.</h3>


![leaderboard](https://github.com/amitrizz/Bugbounty/assets/74492526/cff2d9a9-3f08-4f95-9789-a304070d3cf0)


<br><br>
<h3> Here user finds bugs and submits what bug he/she finds with an explanation.</h3>


![Submit answer](https://github.com/amitrizz/Bugbounty/assets/74492526/3bac43e5-0df3-46b3-9b3b-eda2fc601c3e)


<br><br>
<h3> Here we check the bug give bugid and add a point to the user on the basis of previously submitted bugsid. </h3>


![ReviewSubmission](https://github.com/amitrizz/Bugbounty/assets/74492526/a1a81b5c-97d6-4efb-85ed-50b384f8cf35)




<h1>That is bugbus part</h1>
<br>
<br>
<h3>That is bug one, In that we choose the previous date but this should not happen</h3>

![Bug1](https://github.com/amitrizz/Bugbounty/assets/74492526/1ebcddd7-de50-49fb-8280-2a5e5c2f3da4)

<br><br>
<h3>Middle read More buttton not working</h3>


![bug2](https://github.com/amitrizz/Bugbounty/assets/74492526/44661f76-3662-4421-a340-a8133b4afc00)

<br><br>
<h3>Here Slider Button Not woeking</h3>


![bug3](https://github.com/amitrizz/Bugbounty/assets/74492526/9941785d-8aa5-4c32-980c-afec2ca524ec)

<br><br>
<h3>Here We select a negative number of seats and if we sort on the basis of the price it will sort on the basis of arrival time </h3>


![bug4](https://github.com/amitrizz/Bugbounty/assets/74492526/06aec6de-804f-4df4-995b-c76854382b02)


<br><br>
<h3>If we select Delhi to Trichy it will reverse order on the next page like Trichy to Delhi</h3>


![bug5](https://github.com/amitrizz/Bugbounty/assets/74492526/3e4848a8-27fe-4341-9bba-fdfa7de182b4)

<br><br>
<h3>Here We did payment using SQL injection like giving user name and password as SQL injection query </h3>



![bug6](https://github.com/amitrizz/Bugbounty/assets/74492526/1122522d-fef4-42fc-b006-4270c2326d2a)






