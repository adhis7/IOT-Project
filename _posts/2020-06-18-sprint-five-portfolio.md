---
layout: post
title:  "Sprint 5 Task"
date:   2020-06-04 21:43:20 +1200
categories: jekyll update
---

<h2> Deploy dockerized Noise Graph Web Application and on Dev Server</h2>
<p> In this task, I need to dockerized Noise Graph web Application 
as well as deploy it on Dev Server.</p>
<h2>What I had done</h2>
 <p>
 After getting public ip address of things server database. 
 I am can't able to connect web app to database. Whatever code change in file error message is same sometime different
 and can't dispay graph. I don't know I am suffering from catch problem. I am always clearing laptop 
  catch file but clearing laptop catch does not clear the application file catch there is my main misunderstanding.
     Finally I had solve this problem by 
    clearing catch configuration of Noise Graph web application. By using this command: 
    <ul>php artisan config:clear</ul> 
    And able to display Noise Graph Web App by connecting to Things server
     database as well as successfully deployed in Dev Sever. 
    </p>
<h2>Problem I Face</h2>
<P>In this task I had face permission denied problem finally I shut out this problem. 
lots of time and try to give
 permission  lots of Problem. </P>
 <img src="{{site.baseurl}}/Images/permision denie error.png" width="1500" height="600">
  <br>
  <h4><i>figure: permision denie error. </i></h4>
  <br>
 <p>After fix this problem I had get proxy problem in the time of deployment. while fixed that problem 
 Noise Graph Web App is able to run on Dev Server. Finally, it looks like this till today (date: 2020-06-18).</p>
 <img src="{{site.baseurl}}/Images/server_output.JPG" width="1500" height="600">
 <br>
 <h4><i>figure: output of Noise Graph from Dev Server. </i></h4>
 <br>
 <p>while I am testing Kevin data on things database under data table I found two types of data in there in payload colum
 some data are seen in numeric format where some are in base_64 format. So it might be affect on the output. 
 I saw last data are base on base_64 so i convert payload data into base_64 to intger format.</p>
 <br>
 I test using like clause: 
- SELECT * FROM `data` WHERE dev_id='noise01' and time like '2020-06-04%'
<img src="{{site.baseurl}}/Images/Payload_data.04.JPG" width="1500" height="600">
 <br>
 <h4><i>figure: payload data in numeric format. </i></h4>
 <br>
 <img src="{{site.baseurl}}/Images/Payload_data.18.JPG" width="1500" height="600">
  <br>
  <h4><i>figure: payload data in base_64 format. </i></h4>
  <br>
<h2>What I learn</h2>
<p>In this sprint I came to know how docker file works. And also know 
that how multiple apps run on the server. This is good experience for me.  
<h2>File location of Dockerized Noise Web App</h2>
Finally, I am merge Noise graph web app on<a href="https://gitlab.com/iotop/polykids-project/"> PolyKids repository</a>
 It was not in specific folder we can see it in outside each files. 
