---
layout: post
title:  "Sprint 2 Task"
date:   2020-05-15 21:43:20 +1200
categories: jekyll update
---


<h1>Sprint 2</h1>
<h1>Noise Level Graph</h1>
<p>To display noise level line graph, I used Laravel framework. </p>
<h1>Problem I Face</h1>
<P>While doing this task, it is difficult for me to convert to
 convert base64 form. The Noise Monitoring Sensor receive the data and stored that data by 
 encrypting base64 data form. So, I need to convert that data into integer form and display in
  a graph form. so, it is tricky, finally I did it. And another thing, I made an indexing table 
  to display total count, highest value, lowest value, average value of graph. Highest value and 
  lowest value is din not seen in index table so I face a problem in there. Finally, when I 
  convert tat base64 value into integer it starts to work and start to calculate highest and 
  lowest value in indexing table. </p>
<h1>What I learn</h1>
<p>I had got a chance how to implement google chart to demonstrate statistical data in graph. </p>
<br>
<h1>Final Output</h1>
Finally, I am merge Noise graph web app on<a href="https://gitlab.com/iotop/polykids-project/"> PolyKids repository</a>
under NoiseGraph_Code. If we run it looks like this.<br>
<img src="{{site.baseurl}}/Images/localNoisegraph1.jpg.PNG" width="1100" height="500">
<h4><i>figure: Noise Graph </i></h4>
<br>
