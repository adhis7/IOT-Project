---
layout: post
title:  "Sprint 3 Task"
date:   2020-05-15 21:43:20 +1200
categories: jekyll update
---

<h1>Login Bug fix</h1>
<p> In this task, The Heatmap web application is already build in but the initial assumption is that assumption login function is not working propery, So I need to fix it. Luckly, login function is working properly at the end.  </p>
<h1>Problem I Face</h1>
<P>While doing this task, it is difficult for me to setup the environment of heatmap web app in pycham interperetor becouse I had never done such type of task. And it is difficult to read understand all the code so i split login code and try to fix check it in by initizing new web app and copy and past previous heatmap code and try to fix login bug. At that time i had create a superuser as well as their password from command line  and generate a token using postman application. At that time it works and the login fuction works perfectly new web project without changing orginal code. Here in new web app I had only create new superuser name and password only than I want to try create new superuser from command line in orginal heatmap web app. Finally my supervisor told me that it work perfectly nothing bug in the system now only need to update documentation. And, Bex told me i will update documentation and she update documentation of that project. At last we shutout our misunderstandingness on this task.  </p>
<h1>What I learn</h1>
<p>I came to know how token key is generate and implement in a system a super admin.  

<h1>Some evidence of {{site.baseurl}}/Images are below:</h1>
<p>The given below figure was successfully generate a token if 
given super username and password is valid. I had generate this token becouse I don't know username and password. And I 
test it by same orginal code I found it was working correctly. <br>
<img src="{{site.baseurl}}/Images/MicrosoftTeams-image (1).png" width="1500" height="600">
<br>
<h4><i>figure: token generating successfully </i></h4>
<br>
<p> If given superuser name and password is invalid it will not generate user token.</p>
<img src="{{site.baseurl}}/Images/MicrosoftTeams-image.png" width="1500" height="600">
<br>
<h4><i>figure: fail to generate token </i></h4>
<br>