# Identification-and-characterization-of-SERIOUS-GAMES-on-PlayStore

![image](https://user-images.githubusercontent.com/92247654/187917801-e35c6301-d323-4c49-8856-281d484f5295.png)


- **DATABASE CREATION**: an automatic algorithm in Python 
filters out the serious games among all PlayStore apps based on the category and the description of the app. Using google search library to query for the app name followed by the words
“google play”, the app ID is retrieved when possible and information from it are extracted. 

- **SERIOUS GAMES CHARACTERIZATION**: 
![image](https://user-images.githubusercontent.com/92247654/187918389-11c146ed-51ae-4731-be38-7076590d3a6e.png)

1. **Gooogle Scholar scraping**: implementation of automated generation of the url to research app references on Google Scholar; the url is used by the Python Request module to fetch the data;
BeautifulSoup is used to extract information and to use CSS (Cascading Style Sheets) selectors to query the page for meaningful data; 
3. **Abstract extraction**: to obtain the needed information for the characterization of the serious games;  
4. **Natural Language Processing**: tokenization, POS-tagging, lemmatization. All the steps were done by the usage of nltk library;
5. **Classification of study type**: assessment of the level of clinical evidence produced on 
selected serious games, depending on the type of study carried on in associated papers. This was performed using a provided lists of words characteristic for each study type and counting the number of words in common between the abstracts (after NLP processing) and the four dictionaries. 


---
Contributors: Giulia Peteani, Gloria Rizzato, Francesca Ronchetti, Maria Marchesi, Martina Minotti
