# Politizer
Politize: Empowering Political Consultancies with Data-Driven Insights
Overview
The Politize project is dedicated to addressing the unique challenges faced by political consultancies in today's dynamic landscape. Our mission is to provide a comprehensive solution that leverages data analytics to analyze the influence of news media on political polls. By creating a powerful tool, Politize aims to empower political consultancies and campaigns with actionable insights derived from the intricate relationship between media coverage and polling data.

Key Features
Data Collection: Politize utilizes the newdata.io API to gather news articles from various publishers across the USA. The collected data includes essential variables such as publication date, publisher, title, and description, offering a holistic view of the media landscape.

Data Processing: Our script cleans and structures the raw data, preparing it for in-depth analysis. Natural Language Processing (NLP) algorithms, powered by libraries like Spacy, are employed to filter the dataset for candidate relevance.

Sentiment Analysis: Politize employs Flair models for NLP-based sentiment analysis of news article titles and descriptions. This analysis provides valuable insights into the sentiment surrounding political candidates in the media.

Keyword Extraction: Using Spacy and Vader, a lexicon analysis tool, Politize extracts keywords from news articles and identifies weekly key topics. These insights help in understanding the key issues and trends in media coverage.

Correlation with Poll Data: The project cross-references media data with polling information sourced from legitimate and official sources (e.g., FiveThirtyEight for the Beta Version). This correlation allows for a comprehensive analysis of the relationship between media sentiment and polling results.

Real-time Data Updates: Politize ensures that its dataset is up-to-date in real-time, reflecting the latest media and polling data. This is achieved through job scheduling data pipelines, ensuring that users always have access to the most current information.

The Politizer Dashboard
The final output of the Politize project is the Politizer Dashboard. This user-friendly dashboard offers interactive elements that empower clients to make informed strategic decisions. Users can explore daily sentiment trends, news frequency, and poll percentage estimates, all of which play a crucial role in shaping political campaigns and strategies.

Beta Version
The Beta version of Politizer is currently applied to the 2024 U.S. Primaries, focusing on leading Republican and Democratic candidates. This iteration serves as a valuable proof of concept, showcasing the capabilities of Politize in the context of real-world political campaigns.

Getting Started
To get started with Politize, please refer to the documentation and instructions in the repository. Feel free to contribute, provide feedback, or use Politize to gain insights into the complex interplay between media coverage and political polls.
