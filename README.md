# Code-Mixed Parallel Corpus Analysis for Education

## Abstract

This project aims to facilitate students in the education domain by addressing language barriers. We've created a code-mixed parallel corpus containing Hindi and English, analyzed its characteristics, and leveraged it for developing a machine translation system. The dataset is domain-specific and can be extended for hate speech identification and sentiment analysis.

**Keywords:** Code-Mixed Parallel Corpus, Corpus Analysis, Education Domain

## Introduction

Code Mixing, the use of multiple languages in a single speech, is prevalent in social media. We focus on Neural machine translation, specifically using the Hinglish code-mixed parallel corpus. The dataset, created in the education domain, addresses the scarcity of good parallel data for accurate translation.

### Advantages of the Existing System

- Availability of Large Datasets.
- Constantly updating.

### Disadvantages of the Existing System

- Difficult to read and understand at times.
- Inaccurate results.
- Translation out of context.
- No support for code-mixed translation.
- Lack of domain-specific translation.

## Dataset Collection and Associated Problems

- Main data source: NPTEL.
- Challenges:
  - Not all lectures had both English and Hindi transcripts.
  - Manual copying due to scraping issues.
  - UTF encoding problems in most courses.
- Careful course selection to mitigate problems.

## Dataset Statistics and Analysis

### Quantitative Analysis

#### Monolingual Analysis

- Unigram, Bigram, Trigram
- Type Token Ratio (TTR)
- Moving Average Type Token Ratio (MATTR)

#### Code-Mixed Analysis

- Determination of Matrix Language using the Matrix Language Framework Model (Myers-Scotton).
  1. Word count in the sentence.
  2. Language of verbs.
  3. Language-specific function words.

## Conclusion and Future Scope

### Conclusion

- Monolingual and code-mixed analyses performed.
- Unique and valuable dataset for various applications.

### Future Scope

- Utilization in neural machine translation systems and emotion detection.
- Extending the approach to different language sets.

## Project Structure

- `PROJECT ANALYSIS.ipynb`: Code file.
- `DATASET`: Dataset file.
- `Survey on Readability`: Survey file for readability comparison.
