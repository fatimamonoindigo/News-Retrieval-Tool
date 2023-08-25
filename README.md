# News-Retrieval-Tool

The News Retrievaal Tool is a Python script designed to help users search for and analyze news articles related to specific keywords. The tool retrieves relevant news articles from trusted sources, performs text analysis, and presents the results in a user-friendly interface.

## Features

- **Search and Retrieve:** The tool allows users to input a keyword to search for news articles related to the topic. It utilizes the Google search engine to fetch relevant articles.

- **Content Analysis with NLTK:** The retrieved news articles are analyzed for relevance and accuracy. The tool calculates the relevance of the articles to the search keyword and the accuracy of the article summaries.

- **Trusted News Sources:** The tool relies on a predefined list of trusted news sources to ensure the quality and credibility of the retrieved articles.

- **User-Friendly Interface:** The tool provides a graphical user interface (GUI) using the Tkinter library, making it accessible and easy to use.

## Installation

1. Clone or download this repository to your local machine.

2. Install the required Python packages using the following command:

   ```shell
   pip install -r requirements.txt

## Usage
Run the news_retrieval_tool.py script using the following command:

python news_retrieval_tool.py
The tool's GUI window will open.

Enter a keyword in the provided text field and click the "Run News Scrapper" button.

The tool will fetch related news articles, analyze them, and display the results in the ScrolledText widget.

## Ethical Considerations

**Data Privacy** : The tool respects data privacy regulations and includes user-agent headers to identify itself while scraping. It also checks for the "robots.txt" file to adhere to scraping rules.

**Credibility**: The tool relies on trusted news sources to ensure the credibility of the retrieved articles. However, it's important to regularly review and update the list of trusted sources.

**User Consent**: If user data is being used, ensure that users provide consent and have control over their data.
