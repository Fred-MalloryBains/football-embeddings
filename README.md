# ⚽ Football Embeddings Experiments

This project was part of my University Coursework for Data Mining, where we had to collect, process and report on any 
large set of data. I chose to combine Premier League football match statistics and match reports to analyse sentiment and 
data collected and compare across the different teams of league.

I made use of web scraping techniques using selenium to extract match statistics from sofascore as well as match report/ summaries from 
the premier league website. I implemented techniques such as interaction, politeness windows and ____ before saving all the data into csv 
formatting. 

The data was then processed and cleaned using numpy and pandas so that it could be analysed. To implement analysis I used doc2Vec embeddings to 
create unique vectors for each match followed by each team for visualisation and comparison using PCA.

You can see my results below: 

[📄 View Findings](./FINDINGS.md)

---

## 1. Setup

- **Venv**: python -m venv venv to create virrtual environment
- **Install Requirements**: source venv/bin/activate;pip install -r requirements.txt
- **Jupyter**: jupyter lab  
- **Select file**: open match_reports.ipynb


---

## 2. File Structure

- **Embedding Files**: /main   
- **Data mining files**: /web_scraping
- **Datasets**: /web_scraping
- **Combined Dataset**: match_r_s.csv


---

## 3. How it works

- Using the files you are able to create team embeddings using match report and statistical data
- This data can be explored through the various visulisation methods in the match_report jupyter notebook,
- Further investigation could be done by, comparing different seasons, managers etc,
- commparing cosine similarity and euclidean distance, just the document and just the statistics




