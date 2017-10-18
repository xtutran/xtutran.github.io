---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

### Education
* B.S. in Vietnam, Vietnam National University, 2011

### Work experience
* Jul 2016 - Present: <b>Data Engineer</b> - <i>AXA Data Innovation Lab</i>
  * Data management: cleansing, managing, data-warehousing based-on Hadoop ecosystem 
  * Data modelling: data exploration, feature engineering
  * Industrialize production workflow and data pipelines on E2E environment

* Aug 2015 - Jul 2016: <b>Research Engineer</b> - <i>Singapore University of Technology and Design (SUTD)</i>
  * Worked as a Research Assistant under supervision of Ass. Prof., Zhang Meihui on topic of massive data integration and analytic.
  * Mined logs data of Power Plant system to detect anomaly operations and predict failures: descriptive statistic, association rules mining
  
* May 2013 - Aug 2015: <b>Data Engineer</b> - <i>FTP Software - DIRECTV - AT&T</i>
  * Involved researching and developing a Cloud Recommendation System of DirecTV - Los Angeles, US 
  * Mainly focused on building a recommendation engine based-on content-based filtering and collaborative filtering algorithms
  * Hand-on developed and optimized large-scale ETL jobs based on Hadoop ecosystem: MapReduce, Apache Spark, HBase, Hive, Pig, Oozie Workflow

* Sep 2012 - March 2013: <b>Research Assistant Internship</b> - <i>Singapore Management University</i>
  * Worked under supervision of Ass. Prof. Jing Jiang on unsupervised information extraction topic
  * Studied and implemented some unsupervised machine learning algorithms for text clustering: Gibb sampling (MCMC), Naive Bayesian mixture model, Gaussian mixture model

* Dec 2009 - Sep 2012: <b>Teaching and Research Assistant</b> - <i>Vietnam National University</i>
  * Studied and practised with Data Mining and Natural Language Processing techniques
  * Participated annual student research conference, from 2009 to 2012
  * Involved tutoring students during office hours and lab sections who needed to grade weekly lab reports, grade exams and grade programming assignments, from 2011 to 2012 

### Skills
* Computer Science
  * Programming: Python, Java, Scala, Unix Shell
  * Distributed System: Hadoop ecosystem (HDFS, Hive, Spark, Pig)
  * Message Queue: Kafka, RabbitMQ, ZeroMQ
* Data Science
  * Techniques: Machine Learning, Descriptive Statistics, Financial Data Analytics, Trading Strategy
  * Toolset: pandas, numpy, scikit-learn, keras, tensorflow, Spark mllib

### Publications
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
