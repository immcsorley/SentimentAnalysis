# Sentiment Analysis Project

## Introduction
Welcome to the repository for the sentiment analysis project conducted as part of a text analytics class. This project focused on analyzing sentiment from articles obtained through web scraping, specifically targeting the renowned news outlet, The Hill (www.thehill.com). The Hill is a prominent source of news covering politics, policy, and government affairs in the United States. With its reputation for providing in-depth analysis and reporting on the latest political developments, it serves as a valuable resource for researchers, journalists, and political analysts.

The objective of this project was to scrape articles from different topic categories on The Hill website and explore how sentiment varies based on these topics. The chosen categories for analysis were News, Policy, Business, Opinion, Events, and Jobs. We hypothesized that the sentiment expressed in articles might differ depending on the topic discussed. By grouping articles into these categories, we aimed to conduct independent analyses for each category while also examining the overall sentiment across all articles.

<img width="856" alt="Screenshot 2023-06-08 at 10 03 07 AM" src="https://github.com/immcsorley/SentimentAnalysis/assets/90923213/7bcf311f-4580-426f-8a1e-828fe1f67427">


Through the power of web scraping, we sought to extract valuable insights from The Hill news press website, shedding light on the complex and ever-evolving world of politics and government affairs in the United States. This repository contains the code, documentation, and findings of our sentiment analysis project, providing an opportunity for others to learn from and contribute to our work.

We invite you to explore the repository and discover the methodologies, techniques, and results obtained from this project. By delving into the intricacies of sentiment analysis in a political context, we hope to contribute to the broader field of text analytics and inspire further research in this domain.

In each of the jupyter notebook files you will find our thought process, code, and findings from each step of the process. 

1. **WEB SCRAPING**: The first step we completed was web scraping, which included actually scraping the web pages and saving them to a folder contianing all of the web pages in HTML format. 
2. **PARSING**: The next step was parsing the saved HTML files and extracting the information we wanted, which was the title, author, date and body of the news article. We saved all of these into a single csv file
3. **SENTIMENT CLASSIFIER**: The next step we tokenized the body text and determine if each sentence is a positive, neutral, or negative sentiment. We used these as training data and built various models for prediction. We saved the best model which was a SVM model. 
4. **CLUSTER/TOPIC ANALYSIS**: The last thing we did was perform a cluster and topic analysis using LDA topic modeling. We looked at keywords of each topic the model discovered and found what each topic was mostly talking about. Some topics included political, environmental, financial, and social issues. 



Thank you for your interest in our project, and we look forward to your engagement and feedback.
