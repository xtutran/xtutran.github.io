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
* April 2020 - present: <b>Data Engineering Expert | Tech Lead</b> - <i>AXA Group Emerging Technologies and Data (GETD)</i>
  * Mainly focused on analysing Vehicle / Marine Telematics data to identify important risk factors which impacts claim/loss experience
  * Tech lead - person in charge to architect & develop the very first prototype of near real-time monitoring system which tracks GPS location of thousands vessels/ships insured by AXA XL - Marine Hull insurance. The prototype also send real-time alerts if any vessels gets close to bad weather condition or precautionary areas. This prototype has been running now in production environment and fully managed entire AXA XL portfolio.
  * Tech lead - person in charge to architect & develop a real-time IoT data pipeline which collect/decode sensor's data. This is scalable distributed pipeline fully based on AWS Serverless computing and Sigfox technology.
  * Data Engineering - contribute to core data pipeline of Fraud claim analytics solution which has been used widely across multiple AXA entities (Italy, Belgium, UK, Hong Kong ...)

* June 2018 - April 2020: <b>Senior Data Engineer</b> - <i>AXA REV (Research, Engineering, Vision)</i>
  * Architect production machine learning pipelines for AXA partnership projects with two biggest Banks in APAC (Bank Mandiri Indonesia and Metro Bank Philippines)
  * Conducting multiple data engineering trainings for AXA entities - Krungthai AXA, AXA Mandiri, AXA Philippines

* June 2016 - May 2018: <b>Data Engineer</b> - <i>AXA Data Innovation Lab</i>
  * Data management: cleansing, managing, data-warehousing based-on Hadoop ecosystem 
  * Data modelling: data exploration, feature engineering
  * Industrialize production workflow and machine leanring pipelines on end-to-end environment 

* Aug 2015 - Jul 2016: <b>Research Engineer</b> - <i>Singapore University of Technology and Design (SUTD)</i>
  * Analyzing and detecting anomaly event in log of  Power Plant system: association rules mining, multivariate analysis
  * Massive data integration from multiple data sources: semantic schema matching, knowledge base enhancement (freebase, dbpedia)
  
* May 2013 - Aug 2015: <b>Data Engineer</b> - <i>FTP Software - DIRECTV - AT&T</i>
  * <b>Cloud Recommendation Production</b>, <i>onsite in USA</i>
    * Developed RESTful Web Services to provide data analytics results to end-user interface using Spring MVC, HDFS and HBase
    * Implemented Data quality assessment pipelines: univariate/bivariate profiling, monthly data comparision using Zoomdata, Python viz (matplotlib, seaborn, plotly)

  * <b>Cloud Recommendation POC</b>, <i>offshore in Vietnam</i>
    * Experimented feasible recommendation algorithms which will be deployed on AWS and Hadoop ecosystem: content-based filtering and collaborative filtering
    * Data preparation: developed and optimized large-scale ETLs, mostly are Java MapReduce and Hive jobs

* Sep 2012 - March 2013: <b>Research Assistant Internship</b> - <i>Singapore Management University</i>
  * Worked under supervision of Ass. Prof. Jing Jiang on unsupervised information extraction
  * Studied and implemented some unsupervised machine learning algorithms for text clustering: Gibb sampling (MCMC), Naive Bayesian mixture model, Gaussian mixture model

* Dec 2009 - Sep 2012: <b>Research Teaching Assistant</b> - <i>Vietnam National University</i>
  * Researched on Text Mining and NLP: question answering, pos-tagging, name entity recognition, text summarization
  * Assisted undergraduate students to study CS courses: Data Structure & Algorithms, SQL, Java

### Skills
* Computer Science
  * Programming: Python, Java, Scala, Unix Shell
  * Cloud Computing: AWS, Google GCP
  * Distributed System: Hadoop ecosystem (HDFS, Hive, Spark, Pig)
  * Message Queue: Kafka, RabbitMQ, ZeroMQ
* Data Science
  * Techniques: Machine Learning, Descriptive Statistics, Financial Data Analytics, Trading Strategy
  * Toolbox: pandas, numpy, scikit-learn, keras, tensorflow, Spark mllib

### Publications
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
