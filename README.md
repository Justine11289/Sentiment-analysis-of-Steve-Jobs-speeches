# Sentiment-analysis-of-Steve-Jobs-speeches

# Sentiment Analysis of Steve Jobs' Speeches

Quantifying the oratorical charisma of Steve Jobs, this text mining project employs R-based sentiment analysis to decode the emotional narrative of his most iconic presentations. By applying NRC and Bing lexicons alongside tidy data principles, the system transforms raw speech transcripts into actionable insights, visualizing the strategic use of positive and negative emotional arcs.

## ✨ Project Overview
Steve Jobs was renowned for his powerful storytelling and ability to captivate audiences. This project analyzes specific speech texts—such as the **2007 iPhone launch event**—to measure the ratio of positive to negative emotions and visualize the narrative flow using data science techniques.

### Key Features
* **Text Preprocessing**: Automatically cleans punctuation, numbers, extra whitespace, and common English stop words to prepare the text for analysis.
* **Word Frequency Analysis**: Identifies top keywords used in the speeches and generates **Word Clouds** for intuitive visual representation.
* **Sentiment Quantification**: Integrates sentiment lexicons (such as NRC or Bing) to transform text into measurable emotional indices, tracking the "highs and lows" of the speech.
* **Interactive Reporting**: Provides comprehensive reports generated via R Markdown, allowing users to browse charts and statistics in a web-friendly format.

## 📁 Project Structure
The project is organized as follows:
```plaintext
Sentiment-analysis-of-Steve-Jobs-speeches/
├── speech.txt          # Raw text data containing the speech transcript
├── Iphone.Rmd          # Core R Markdown source code for analysis
├── iPhone.html         # Automatically generated interactive analysis report
├── Report.pptx         # Project summary and results presentation
├── Report.rar          # Compressed archive containing all project resources
└── README.md           # Project documentation and guide
```
## Technical Stack
* Language: R
* Core Packages:
  * `tm`: For text mining and corpus processing.
  * `tidytext`: For sentiment analysis and tidy data principles.
  * `wordcloud`: For generating visual tag clouds.
  * `ggplot2`: For advanced data visualization and emotional trending.
  * `rmarkdown`: For creating dynamic and reproducible HTML documents.
## How to Use
* Environment Setup: Ensure you have R and RStudio installed on your system.
* Run Analysis: Open `Iphone.Rmd` in RStudio and click the "Knit" button. The system will process `speech.txt` and generate the latest `iPhone.html` report.
* View Results: Open the generated `iPhone.html` file in any web browser to explore the sentiment charts and word frequency statistics.

### Video
[![iPhone新品發表會-賈伯斯講稿分析](https://img.youtube.com/vi/zOPjJkUorqg/maxresdefault.jpg)](https://www.youtube.com/watch?v=zOPjJkUorqg)
