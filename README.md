# SentimentStream
A real-time news aggregator with sentiment analysis, summarizing articles and providing emotional insights using advanced NLP techniques.

# SentimentStream

SentimentStream is a dynamic news aggregation tool that curates real-time articles from various sources and enhances each story with sentiment analysis. Using advanced natural language processing techniques, SentimentStream provides summaries and sentiment insights for each article, allowing users to quickly gauge the mood of trending topics.

## Features
- **Real-time News Aggregation**: Fetches the latest news articles based on user-specified keywords.
- **Dual Sentiment Analysis**: Uses both VADER and TextBlob models to provide balanced sentiment insights.
- **Summarization**: Summarizes articles for quick reading.
- **Data Storage**: Saves article data and sentiment analysis in a SQLite database for easy access.
- **Export to Excel**: Outputs news feed data to an Excel file for convenient offline access.

## Getting Started

### Prerequisites
- [Google Colab](https://colab.research.google.com) for running the Jupyter notebook.
- A NewsAPI key for fetching articles ([NewsAPI](https://newsapi.org)).

### Usage
1. Open the `SentimentStream_Analysis.ipynb` notebook in Google Colab.
2. Add your NewsAPI key in the appropriate cell.
3. Run all cells to fetch news, summarize content, analyze sentiment, and export results to an Excel file.

### Files
- `SentimentStream_Analysis.ipynb`: Jupyter notebook for running the entire pipeline, from data fetching to sentiment analysis and export.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request for any improvements.


