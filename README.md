
# Exploratory Data Analysis on Spotify 2023 Dataset

This project conducts an Exploratory Data Analysis (EDA) on a dataset of popular Spotify tracks. Through data cleaning, visualization, and statistical analysis, it uncovers trends and insights into what makes a song popular on the platform. Key features such as genre, popularity score, release year, and audio characteristics (like danceability, energy, and tempo) are examined to reveal patterns in popular music. The findings from this analysis can help in understanding music trends, identifying features correlated with popularity, and providing a data-driven foundation for further exploration.

## Problems Encounter and Resolving: 

1. On October 26, 2024, I encountered a UnicodeDecodeError while attempting to load my dataset. I was new with this problem, so troubleshooting took some time. After browsing the Kaggle discussion forums, I noticed that adding encoding='latin1' to my code could resolve the issue. To confirm where to apply this change, I consulted ChatGPT, which assisted me in correctly applying the fix.
   
```python
sp = pd.read_csv('spotify-2023.csv', encoding='latin1') 
```



## Timeline and Changelog

| Date       | Version | Description                                     |
|:-----------|:-------:|------------------------------------------------:|
| 2024-10-26 | 1.0  | I began developing the code and have progressed to the point where I’m generating summary statistics |
| 2024-11-10 | 1.1  | Added data processing module, improved README. |
| 2024-11-15 | 1.2  | Fixed bug in data parsing, optimized functions. |
| 2024-11-20 | 1.3  | Enhanced documentation, added usage examples.   |

