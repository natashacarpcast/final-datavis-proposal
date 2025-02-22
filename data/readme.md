
# Data

## Data source

All comments and submissions from three subreddits (r/selfimprovement, r/investing and r/homeowners) were obtained through [Academic Torrents](https://academictorrents.com/details/56aa49f9653ba545f48df2e33679f014d2829c10). The original datasets included each entry's id, text, date etc.  

## Data cleaning and processing

Data cleaning and previous processing were done on earlier stages of my project (standard steps such as removing missing values, cleaning the text (lowercasing, removing punctuation), deleting very short text, etc.). Although this was not necessary for using the LIWC software, it was done for other steps of the project.

Thus, the cleaned data was later used in the LIWC software to obtain scores for the LIWC's moral dimension and positive emotion/negative emotion, as well as scores for another dictionary: The Moral Foundation Dictionary (MFD).

Topic modeling was used using the Gensim library using the same data. 

## Final data

The [final dataset](final_data.csv) presented here has the following columns: 

- "id": submission/comment unique identifier
- "cleaned_text": cleaned text from the submission/comment
- "dominant topic": the most probable topic for a document
- "moral": LIWC's moral dimension score
- "Sanctity_Vice": MFD Sanctity Vice score
- "Sanctity_Virtue": MFD Sanctity Virtue score
- "Sanctity_total": Aggregated score for Sanctity's Vice and Virtue scores
- "Care_Vice": MFD Care Vice score
- "Care_Virtue": MFD Care Virtue score
- "Care_total": Aggregated score for Care's Vice and Virtue scores
- "Fairness_Vice": MFD Fairness Vice score
- "Fairness_Virtue": MFD Fairness Virtue score
- "Fairness_total": Aggregated score for Fairness's Vice and Virtue scores
- "Loyalty_Vice": MFD Loyalty Vice score
- "Loyalty_Virtue": MFD Loyalty Virtue score
- "Loyalty_total": Aggregated score for Loyalty's Vice and Virtue scores
- "Authority_Vice": MFD Authority Vice score
- "Authority_Virtue": MFD Authority Virtue score
- "Authority_total": Aggregated score for Authority's Vice and Virtue scores
- "Virtue_total": Aggregated score for all virtue's scores
- "Vice_total": Aggregated score for all vice's scores
- "Foundations_total_score": Aggregated score for all foundations' scores. 
