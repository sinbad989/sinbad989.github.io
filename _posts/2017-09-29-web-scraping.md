---
layout: post
title: "Web Scraping Lotto Data"
date: 2017-09-29
category: programming 
tag: web scrapping
---
<div style="text-align: justify;">
The internet is loaded with data waiting to be extracted. Web scraping is data scraping used for extracting data from websites. Any content that can be viewed on a webpage can be scraped. Many available Web scraping tools and software automates this task. In this article, I intend to show how one can web scrap data from a lotto archive using python, more specifically the BeautifulSoup library.

<br>
<br>
Web scrapping is one of the important skill one should learn if one wants to be a data scientist.

<br>
<br>
The data we're going to extract are from: <a href="http://www.lotto-archive.com">http://www.lotto-archive.com</a>


<br>
<br>
<ol>
<li> <b>Importing the necessary libraries</b>
<script src="https://gist.github.com/sinbad989/1de26a6adb828ac819f5db736271e03e.js"></script>
</li>

<li> <b>Extracting the necessary data</b>
<script src="https://gist.github.com/sinbad989/da36dcaf8aa1b5b2d5a20c1a7fcf846d.js"></script>

<script src="https://gist.github.com/sinbad989/8ef629206b2ee1746728a392bd29c6ae.js"></script>
The result of the head of our dataframe. (df.head())
<br>
<img src="{{site.url}}/img/4.PNG">
<br></li>

<li> <b>Saving the extracted data into a file</b>

<script src="https://gist.github.com/sinbad989/578b485b9d6a7657facb29f09068b283.js"></script>
<br>
</li>
</ol>
<b>Conclusion: </b><br>
The collected data contains 1815 entries. It's now ready for data analysis or machine learning exploitation. Basically, the thing you do in scrapping is the same as what we have done using the three steps. With some added details to guide and make your data extraction efficient and purposeful. 
<ol>
	<li>What data do you want and where can you get it.</li>
	<li>Software Workflow:</li>
	<ol>
		<li>Importing the necessary libraries</li>
		<li>Extracting the necessary data</li>
		<li>Saving the extracted data into a file</li>
	</ol>
	<li>What data analysis can you do with the data you have?</li>
</ol>
<br>
<br>
</div>
