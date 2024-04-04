WhatsApp Chat Analyzer

Introduction

The WhatsApp Chat Analyzer is a web application designed to analyze and visualize
various aspects of WhatsApp chat data. The application allows users to upload a
text file containing WhatsApp chat data, and then provides various statistical and
visual analysis features. These features include top statistics, monthly and daily
timelines, activity maps, and most busy users. 

Tech Stack
The application is built using the following tech stack:
● Python: The primary programming language used for developing the
application. ● Streamlit: A Python library used for building interactive data applications. ● Pandas: A Python library used for data manipulation and analysis. ● Matplotlib: A Python library used for creating static, animated, and interactive
visualizations in Python. ● Seaborn: A Python data visualization library based on Matplotlib. It provides a
high-level interface for drawing attractive and informative statistical graphics. ● Re: A Python library used for regular expressions. ● WordCloud: A Python library used for generating word clouds from text data. 

File Structure
The application is divided into three main files:
1. app.py: This file contains the main application logic and user interface. It
handles file uploads, user interactions, and data analysis. 
2. preprocessor.py: This file is responsible for preprocessing the uploaded
WhatsApp chat data. It extracts relevant information, such as user messages
and dates, from the raw data and converts it into a pandas DataFrame. 
3. helper.py: This file contains various helper functions used throughout the
application. These functions are responsible for fetching statistics, creating
word clouds, and performing other data analysis tasks.

Features
The WhatsApp Chat Analyzer provides the following features:
● Top Statistics: Displays the total number of messages, total number of words, number of media messages, and number of links shared. ● Monthly Timeline: Shows the number of messages sent each month. 
● Daily Timeline: Shows the number of messages sent each day. 
● Activity Map: Provides a heatmap of user activity, showing the busiest day
and busiest month. 
● Most Busy Users: Lists the users who have sent the most messages in the
group. 
● WordCloud: Generates a word cloud based on the most frequently used
words in the chat.
● Most Common Words: Displays a bar chart of the most common words used
in the chat. 
● Emoji Analysis: Shows a pie chart of the most frequently used emojis in the
chat. 

Usage
To use the WhatsApp Chat Analyzer, follow these steps:
1. Upload a text file containing WhatsApp chat data. 
2. Select a user or group to analyze. 
3. Click the "Show Analysis" button to view the analysis results. 

Conclusion
The WhatsApp Chat Analyzer is a powerful tool for analyzing and visualizing
WhatsApp chat data. It provides valuable insights into user activity, communication
patterns, and popular words and emojis used in the chat. This information can be
useful for understanding group dynamics, identifying trends, and improving
communication strategies.