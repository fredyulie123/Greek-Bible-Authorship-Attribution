# Greek-Bible-Authorship-Attribution
This project is about Authorship Attribution of the epistles of Hebrews by using text mining methods. 

## Data Gathering
In this project, we gathered three versions Greek New Testament bible from websites (Novum Testamentum Graece 28th edition--- usually known as NA28, Tyndale Bible, Greek New Testament published by Logos Bible Software and the Society of Biblical Literature--- usually known as SBLGNT)
We used **Selenium** and **BeautifulSoup** to scrape the data

## Data processing
We used three NLP tools to split data to tokens (NLTK/SpaCy/Stanza)

## Data Analyzing

### Lexical Analysis
in this project, we used several indexes (cosine similarity/jaccard distance/jensen-shannon divergence/dice coefficient/hellinger distance) to compare the document similarities between the epistles of Hebrews with other books in New Testament

### Syntactic Analysis
in this project, we used Bi-direction LSTM model to compare the syntactic similarities between the epistles of Hebrews with other books in New Testament
