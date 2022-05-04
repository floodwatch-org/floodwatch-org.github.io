---
layout: default
title: About FloodWatch
lang: en
---

<div class="post">
	<h1 class="pageTitle">What is FloodWatch?</h1>
    <h1>A Deeper Look</h1>
    <p class="intro">FloodWatch is a mobile application focused on flood forecasting and alerting in Ho Chi Minh City and other cities throughut Vietnam. Leveraging both research and user-sourced data, FloodWatch is able to identify areas of high-risk flooding.</p>
    <img src="{{ '../floodwatchappdesign.png' }}" alt=""><br/>
    <h2>Technology Used</h2>
	<ul>
  	<li>AWS Lambda for machine learning processing and handling of requests</li>
  	<li>AWS Relational Database Service (RDS) for storing historical readings and predictions by location</li>
  	<li>React Native for consumer facing application</li>
	<li>Mapbox for rendering overlays with flood data and user reports on a map interface</li>
  	</ul>
    <h2>The Data Pipeline</h2>
    <p>A data pipeline is a series of data processing steps to transform data from one form to another. The current model automates data intake from HEC-RAS via shared virtual instance. Upon intake, data is uploaded to Amazon servers, and sent to MapBox. MapBox then renders data onto map overlays that can then be fit on top of our front facing map interface in the application.</p>
	<img src="{{ '../DataPipeline.PNG' }}" alt=""><br/>
</div>
