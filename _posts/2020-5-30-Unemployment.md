---
layout: post
comments: true
title:  "Unemployment in the US during Covid: An Overview with Data Visualization"
excerpt: "There have been a lot of news about increased unemployment in the US due to the pandemic (i.e. covid 19) lately. So I decided to scrape some data from a couple of recently published reports on the websit of Bureau of Labor Statistics and do a quick exploratory data analysis. This short writeup outlines my finidings."
date:   2019-09-29 01:00:00
mathjax: true
---

# Introduction

Covid 19 has affected all of our lives in many ways. The job landscape is reported to have changed drastically in the US. Many of the friends I talked to were of the opinion that while many sectors experienced hiring freeze or layoffs, some sectors have also seen an uptick in employment opportunities as we continue to adjust our lives to this new normal. So I decided to scrape the data from some of the reports published on May,2020 on the [website](https://www.bls.gov/) of Bureau of Labor Statistics, and then do some visualizations to educate myself on the trends. The notebook can be found [here]()

Below are the takeaways from it:

# US Workforce: Trends and Distribution from 2019-2020

The total nonfarm (i.e. all employees except farm workers, private household employees, or non-profit organization employees) employees in the US can be grouped into to two major categories or super-sectors - Goods-producing industries and Service-providing industries. The barplot below (Figure 1) shows the distribution the US workforce in these two supersectors over the years while the line plot represents the total employment over the year. As of April 2019, around 86% of the US workforce are employed in the service providing industries whereas the reamining 14% are employed in the goods-producing industries. The chart shows that while roughly 20.53 millions lost their jobs only during the pandemic (i.e., March 2020 - April 2020), their distribution in these two super sectors remained the steady over the year and during this pandemic.

<img src="/assets/Unemployment/US_Workforce_Trends.png">


# Snapshot: Goods-producing vs Service-providing Industries
 
The goods-producing industries largely comprises of manufacturing and construction and contributed to employ roughly ~20 millions americans as of March, 2020 (Figure 2). The major industries in the service providing sector are education and health services, government institutions, trade and transporation as well as professional and business services. Each of these four subgroups in the service -providing sector alone provided more jobs (>20 millions) for americans than the goods-producing sector.


<img src="/assets/Unemployment/unemployment_by_sector.png">


# Unemployment during Covid: Ranked by Industries
Figure 3 charts the number of layoffs (i.e. increase in unemployment) in ranked order from top to bottom. All the industries across the US were negatively impacted due to the pandemic. The Leisure and Hospitality Industry was hit the hardest. Roughlly 46.7% (~7.6 millions) of the americans working in this sector lost their jobs between March - April 2020 due to the pandemic. The number of job cuts in the Education and Health Services came as a surprise given the increasing need of support required at the hospitals at the moment, but it is possible that any possible uptick of hiring in the hospitals was offset by layoffs in other non-emergency services in the health or education sector. The top 3 sectors in the chart taking the worst hit of the pandemic represented 45.4% of the US workforce in March 2020. 

To help further evaluate the impact on different industries, percentage reduction of workforce in all industries are ranked and listed in the table next to Figure 3.   Based on the total number of employments in March 2020 and lay offs over the month, americans working in Financial Services (represents 5.6% of total US workforce) and government institutions (represents 15% of the US workforce) were relatively safer when comes to remaining employed. Both sectors experienced less than 5% decrease in their respective workforce

<img src="/assets/Unemployment/unemployment_by_sectors.png">

# Unemployment during Covid: Ranked by Industries



