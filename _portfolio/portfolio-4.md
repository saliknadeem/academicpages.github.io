---
title: "Twitter Network Analysis"
excerpt: " <img src='/images/tw_comm.png' style='width:1500px;'> | *Creates a network graph of all users involved in the dissemination of a query (keyword, hashtag, meme, etc.) and analyzes trends/connections between the users.* <br/> <br/> 
Developed using: **Python, Tweepy (Twitter API), Ploty, Geopy and NetworkX**<br> 
[Project report](/files/tw_report.pdf) "
date: "April 2019"
collection: portfolio
priority: "04"
---


<img src='/images/tw_data_example.png'>

A python based framework for searching Twitter using a keyword query which can be either a Hashtag or a URL. The program returns all tweets containing that query along with a lot of meta data. Our algorithm then creates a network of all the users involved in sending that tweet and creates a directed graph with users who tweeted that query as nodes and edge direction showing a “followed by” relationship (i.e. the direction in which information flows on Twitter).




<img src='/images/tw_OntarioTech_graph.png'>

***[Project report](../../files/tw_report.pdf)***


This project was an implementation of [Concolic Testing for Deep Neural Networks](https://arxiv.org/abs/1805.00089).