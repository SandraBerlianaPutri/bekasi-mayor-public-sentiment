## YouTube Comment Analysis Using LDA

### About
This project analyzes public YouTube comments related to the Mayor of Bekasi using web crawling, text preprocessing, and Latent Dirichlet Allocation (LDA) to identify discussion topics.

### Data
- **Source:** YouTube comments
- **Collection Method:** YouTube Data API
- **Unit of Analysis:** Comments and replies
- **Data Type:** Text data

### Methods
1. **Data Collection** — Retrieve YouTube comments and replies using the YouTube Data API.
2. **Data Cleaning** — Remove duplicate comments, mentions, hashtags, URLs, emojis, numbers, and unnecessary characters.
3. **Case Folding** — Convert text to lowercase.
4. **Tokenization** — Split comments into individual words.
5. **Normalization** — Convert informal words into standardized Indonesian.
6. **Stopword Removal** — Remove common words with limited analytical value.
7. **Stemming** — Reduce words to their root forms.
8. **Unigram Analysis** — Build a dictionary and examine word frequencies.
9. **LDA Topic Modeling** — Train LDA models and determine the topic count using coherence scores.
10. **Visualization** — Present topic distributions, word clouds, and interactive topic maps using pyLDAvis.

### Author
**Sandra Berliana Putri** - Statistics and Data Science graduate from IPB University, interested in data analysis and machine learning.
