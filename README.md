# Playstore_app_review_analysis

## **Project Details -**
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights an be drawn for developers to work on and capture the Android market. Each app(row) has values for category, ratin, size, and more. Another dataset contains customer reviews of teh android apps. Explore and analyse the data to discover key factors responsible for app engagement and success.

## **Project Summary -**
The Play Store apps data has enormous potential to drive app-making businesses to success. Actionable insights can be drawn for developers to work on and capture the Android market. Each app(row) has values for category, rating, size, and more. Another dataset contains customer reviews of the android apps. In this project we explored and analysed the data to discover key factors responsible for app engagement and success.

We started the projects by understanding our datasets and at the same time cleaning it. However, cleaning the data was a tedious task. We encountered null values, wrong values and some outliers as well. We cleaned the data by dropping the null values or replacing them with mode or mean, as per the need of the situation.

After cleaning the data, we started the analysing our data sets keeping business perspective in mind. The insights we drawn were then represented with the help of questions. Those questions were then answered with help of suitable plots followed by subsequent comments in form of questions and answers. Choice of plots were done keeping in mind the ease of depicting the trends in data, without infusing with unnecessary details. We made use of python modules like pandas, NumPy, matplotlib and seaborn to achieve our objectives.

After the process of preparing, cleaning, plotting, changing and saving(showing), our EDA on play store data analysis project completed. It helped in understanding the data more comprehensively and presenting our insights in lucid manner.

## **Problem Statement & Business Objective**
"Many businesses and developers face challenges in understanding user sentiments, feedback, and preferences from the vast amount of reviews posted on the Google Play Store for their mobile applications. Extracting meaningful insights from these reviews manually is time-consuming and often lacks accuracy. As a result, there is a need to develop an automated solution using natural language processing (NLP) and sentiment analysis techniques to efficiently analyze app reviews. The objective is to gain actionable insights that can help improve app quality, enhance user satisfaction, prioritize feature development, and make data-driven decisions to boost user acquisition and retention. The solution should provide an efficient, scalable, and accurate means of processing and categorizing large volumes of reviews to aid in brand reputation management, competitive analysis, and product roadmap planning."

## Business Objective

The business objective of conducting Play Store app review analysis is to gain valuable insights and feedback from users who have used or are currently using a particular app. By analyzing the reviews and feedback left by users, businesses can achieve several goals:

1 Improve App Quality: App reviews often contain feedback about bugs, crashes, and other issues. Analyzing these reviews can help developers identify problems and make improvements to enhance the overall app quality.

2 User Satisfaction: Understanding user sentiments and preferences expressed in reviews can help businesses gauge user satisfaction levels. Positive reviews can highlight features users love, while negative reviews can shed light on areas that need improvement.

3 Feature Prioritization: Analyzing reviews can help businesses identify popular features and functionalities that users appreciate the most. This data can be used to prioritize future development efforts.

4 Competitive Analysis: Comparing app reviews with those of competitors can offer valuable insights into strengths and weaknesses. This can help businesses identify opportunities to differentiate themselves and improve their market position.

5 User Acquisition and Retention: Positive reviews and high ratings can attract more users to download the app, improving user acquisition. Additionally, addressing negative reviews and resolving user issues can lead to higher user retention rates.

**Introduction of Data**

Mobile applications are widely available. They are simple to make and may be profitable. These two reasons have led to an increase in the number of apps being created. In this notebook, we'll compare more than 10,000 Google Play apps from various categories to conduct a thorough analysis of the Android app industry. In order to develop strategies to promote growth and retention, we will search the data for insights.

Let's examine the data, which consists of the following two files:

This file contains all the details of the apps on Google Play. There are 13 features that describe a given app.

**App: Name of the app
Category: Category of the app. Some examples are: ART_AND_DESIGN, FINANCE, COMICS, BEAUTY etc.

Rating: The current average rating (out of 5) of the app on Google Play

Reviews: Number of user reviews given on the app

Size: Size of the app in MB (megabytes)

Installs: Number of times the app was downloaded from Google Play

Type: Whether the app is paid or free

Price: Price of the app in US$

Content Rating: A content rating (also known as maturity rating) rates the suitability of TV broadcasts, movies, comic books, or video games to its audience.To show which age group is suitable to view media and entertainment.

Genres: A category of artistic, musical, or literary composition characterized by a particular style, form, or content

Last Updated: Date on which the app was last updated on Google Play

Current Ver: Current Version means a version of the software that is currently being supported by its publisher.

Android Ver: Android versions (codenames) are used to describe the various updates for the open source Android mobile operating system.**

This document showcases a selection of the top 100 first-user evaluations for each app. Each category's distribution of favorable and unfavorable reviews has been pre-processed and run through a sentiment analyzer.
**
App: Name of the app on which the user review was provided. Matches the App column of the play_store_data.csv file

Translated Review: The pre-processed user review text.

Sentiment: Sentiment category of the user review - Positive, Negative or Neutral.

Sentiment Polarity: Sentiment score of the user review.**

