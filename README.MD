# Analyzing Justin Bieber’s Purpose and Justice Albums: A Comparative Study of Themes, Sentiments, and Keywords

![HOUSING](https://images.genius.com/cff977262de4bf712a530580d27c7412.1000x1000x1.jpg)


## Introduction
This project is a comprehensive analysis of two significant albums by Justin Bieber: Purpose (2015) and Justice (2021). The analysis explores the thematic evolution, emotional tones, and keyword significance across these albums, reflecting the artist’s journey from personal struggles to broader societal concerns.

## Personal Motivation
The choice to analyze Purpose and Justice stems from a deep personal connection to these albums. When Purpose was released, it resonated with me during a challenging time as a foreign student in Japan. As a young person adapting to a new culture, living independently, and facing various personal challenges, the introspective and redemptive themes of Purpose provided solace and inspiration. The album not only marked a significant moment in Justin Bieber’s life but also in mine, symbolizing a shared journey of finding purpose after feeling lost.

On the other hand, Justice represents a different stage in life—both for Bieber and myself. While Purpose focused on self-discovery, Justice reflects a broader perspective, addressing societal issues and personal relationships. The evolution in Bieber’s music mirrors my own growth, making this analysis not just an academic exercise, but a personal reflection on the themes of purpose and justice in our lives.

## Project Structure
### 1. Data Collection and Preprocessing
- The lyrics from Purpose and Justice albums were collected and cleaned to remove unnecessary text, punctuation, and stopwords.
- The cleaned lyrics were then split into training and testing datasets for further analysis.

### 2. Thematic Analysis
- Objective: Identify recurring themes, topics, or key phrases in the lyrics.
- Methods: Word frequency analysis and topic modeling were used to uncover underlying themes in the lyrics.
- Results: The analysis revealed that Purpose focuses on self-discovery and personal challenges, while Justice deals with broader societal issues and love.

### 3. Sentiment Analysis
- Objective: Quantify the emotional tone of each album to support the thematic differences.
- Tools: Sentiment analysis tools like VADER were used to score each song’s lyrics.
- Results: The overall sentiment scores suggested that Purpose has a more positive emotional tone compared to Justice, which aligns with the personal introspective nature of Purpose versus the broader societal focus of Justice.

### 4. Keyword Analysis (TF-IDF)

- Objective: Identify and compare the most important keywords across the two albums.
- Tools: TF-IDF was applied to highlight significant keywords in each album.
- Results: Keywords in Purpose emphasized personal reflections with terms like “mean” and “make,” while Justice highlighted societal and relational themes with keywords like “need,” “love,” and “life.”

### 5. Sentence Length Analysis

- Objective: Analyze the distribution of sentence lengths to understand the complexity of the lyrics.
- Results: The analysis showed varied sentence lengths in both albums, reflecting the complexity of the themes discussed.

## Recommendations
- Text Classification: While we attempted text classification to differentiate between the albums based on lyrics, the small dataset size limited the effectiveness. Future efforts should involve a larger dataset to improve the accuracy of classification models.
- Applications to Other Domains: The methodologies applied in this analysis can be extended to various domains such as customer reviews, social media sentiment tracking, and literary analysis. These techniques can help extract meaningful insights and patterns from text data in different contexts.
- Future Research: Expanding the dataset to include more songs or even different artists can provide a broader perspective and allow for comparative analyses across genres or time periods.

## Conclusion
This project offers a detailed exploration of Justin Bieber’s Purpose and Justice albums, revealing the evolution of themes, sentiments, and significant keywords. By combining personal reflection with rigorous analysis, this study highlights the transformative journey of the artist and offers insights into the emotional and thematic depth of his music.

## How to Run the Project
1.	Environment Setup: Ensure you have Python installed along with the necessary libraries such as pandas, nltk, matplotlib, seaborn, sklearn, and wordcloud.
2.	Data Files: The dataset used for this analysis includes the lyrics from Justin Bieber’s Purpose and Justice albums, which can be found in the justin_bieber_lyrics_cleaned_final.csv file.
3.	Execution: Run the provided Jupyter notebook (justin_bieber_analysis.ipynb) to reproduce the analysis, including thematic, sentiment, and keyword analysis, along with visualization steps.

## Acknowledgments
Special thanks to my mentor and colleagues for their guidance and support in completing this project. This analysis would not have been possible without the foundational knowledge and tools provided during my studies.