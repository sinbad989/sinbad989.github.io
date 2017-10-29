---
layout: post
title: "Web Scraping Lotto Data"
date: 2017-09-29
category: programming 
tag: web scrapping
---
The internet is loaded with data waiting to be extracted. Data extraction can sometimes be a repeated task. This is were automation of such process is required. Web scraping automates this task.
Web scrapping is one of the important skill one should learn if one wants to be a data scientist. One interesting data to explore are lotto results. Various statistics can be explored on this data.

The data we're going to extract are from: <a href="http://www.lotto-archive.com">http://www.lotto-archive.com</a>



## 1. Importing the necessary libraries
<script src="https://gist.github.com/sinbad989/1de26a6adb828ac819f5db736271e03e.js"></script>

## 2. Extracting the necessary data
<script src="https://gist.github.com/sinbad989/da36dcaf8aa1b5b2d5a20c1a7fcf846d.js"></script>

<script src="https://gist.github.com/sinbad989/8ef629206b2ee1746728a392bd29c6ae.js"></script>
The result of the head of our dataframe. (df.head())

![Imported modules]({{site.url}}/img/4.PNG)
## 3. Saving the extracted data into a file

<script src="https://gist.github.com/sinbad989/578b485b9d6a7657facb29f09068b283.js"></script>


