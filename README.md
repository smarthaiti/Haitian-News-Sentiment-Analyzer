# Haitian-News-Sentiment-Analyzer

Creating a tool to analyze the cumulative sentiment from articles that match a query. The tool collects the relevant articles, cleans the text in preparation for analysis, creates a sentiment score for each article, saves the scores to a new column in the dataframe, then creates a timeseries plot showing the change in sentiment of the given query over a selected time. 

This notebook uses the name of the late president "Jovenel Moise" as a demo and shows a sharp decline in sentiment across news sources on January 1st, 2021. It also outputs a bar graph showing the degree to which each news source published either positive or negative articles during the chosen timeframe. 

The use cases of this kind of tool include marketing, investigative journalism, intelligence and counterintelligence, among other use cases.
