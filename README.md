# seo-tweet-generator-

# SEO Tweet Generator

Automated tweet generation using TF-IDF keyword extraction and NLP. Reads documents and creates 4 SEO-optimized tweet variations with relevant hashtags and emojis.

## Features

- Extracts top 5 keywords using TF-IDF from `.docx` or `.csv` files
- Generates 4 tweet styles: Professional, Viral/Bold, Curious/Teaser, News-style
- Auto-adds relevant emojis and hashtags
- Keeps tweets under 500 characters
- Exports all tweets to downloadable `.docx` file

## Technologies

- **Python** – Core logic
- **scikit-learn** – TF-IDF keyword extraction
- **python-docx** – Document processing
- **Google Colab** – Notebook environment

## Installation

```bash
pip install python-docx scikit-learn
```

## Usage

1. Upload `.docx` or `.csv` file to Google Colab
2. Run all cells[3]
3. Download generated `all_optimized_tweets.docx` with 4 tweet variations

## How It Works

1. Reads and cleans input text
2. Extracts top 5 keywords using TF-IDF vectorization
3. Matches keywords to emoji dictionary
4. Creates 4 tweet variations with different tones
5. Adds hashtags and emojis automatically
6. Exports to Word document

## Example Output

```
Professional:
Here's what you need to know about AI and relevance of AI today. Recent breakthroughs show... #AI #Tech 🤖

Viral/Bold:
AI is catching everyone's attention — and for good reason. 🔥 The latest developments... #AI #Tech 🤖
```

