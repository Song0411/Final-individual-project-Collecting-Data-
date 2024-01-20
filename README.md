# 🎵 K-POP-Group-English-Song-Lyrics-Dataset

**This dataset is a curated collection of English song lyrics by various K-pop groups. It aims to provide a comprehensive resource for linguistic analysis, sentiment analysis, and cultural studies focusing on the K-pop genre.**

## Target Audience and Intended Use
The primary audience for this corpus includes linguists, data scientists, and K-pop enthusiasts interested in text analysis and natural language processing. It's also suitable for educational purposes in computational linguistics courses and for cultural studies researchers analyzing trends in K-pop music.

## Text Selection Criteria
Songs were selected based on their popularity, representation of different K-pop groups, and diversity in themes and styles. The focus was on English lyrics to cater to a wider global audience and to facilitate linguistic analyses that require less translation work.

## Data Collection Process
The lyrics were manually collected through a process of copying and pasting from various online sources. Care was taken to ensure the sources were reliable and the lyrics accurately represented the songs.

## Cleaning and Preprocessing
The collected lyrics underwent several preprocessing steps:  
🎵 Removal of special characters and extraneous whitespace.  
🎵 Conversion of all text to lowercase for uniformity.  
🎵 Tokenization, lemmatization, and parts-of-speech tagging using spaCy for linguistic analysis.  
🎵 Sentiment analysis to determine the emotional tone of the lyrics.  

## Annotations and Tools
The dataset includes several annotations:  
Title: The title of the song. 
Lyrics: The original lyrics of the song. 
Cleaned_Lyrics: Lyrics after preprocessing. 
Tokens: Tokenized lyrics. 
Lemmas: Lemmatized lyrics. 
POS: Parts-of-speech tags for the lyrics. 
Polarity: Sentiment polarity of the lyrics. 
Subjectivity: Sentiment subjectivity of the lyrics. 
Tools used for these annotations include Python's spaCy library for NLP tasks, TextBlob for sentiment analysis, and pandas for data manipulation.

## Dataset Format and Column Description
The dataset is available in CSV format with the following columns:  
🎵 Title: Name of the song.  
🎵 Cleaned_Lyrics: Lyrics after preprocessing.  
🎵 Tokens: Tokenized lyrics.  
🎵 Lemmas: Lemmatized lyrics.  
🎵 POS: Parts-of-speech tags for the lyrics.  
🎵 Polarity: Sentiment polarity score.  
🎵 Subjectivity: Sentiment subjectivity score.  

## Copyright Notice
This dataset is intended for academic and research purposes only. All lyrics have been processed and do not contain the original text to comply with copyright laws. Users of this dataset are advised to respect copyright rules and regulations.
