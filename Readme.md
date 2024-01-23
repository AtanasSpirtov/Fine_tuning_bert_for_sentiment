## Process
1. Download The news links and content with the help of newspaper3k
2. Save the news links in output.csv
3. Getting content of the news and save in raw_news_data.csv
4. Start summarizing news using Falconsai/text_summarization model which is fine tuned T5
model for text summarization.
5. After that the summarized news are saved in summarized_news.csv
6. The next step is manually clear junk data
which is not english and not in the topic 
(this process has to be automated using language detectors)
7. The filtered data is inside ranked_and_filtered_news.csv
8. The last step is preprocessing data and training model


# If you dont want to wait more than 2 days get the `ranked_and_filtered_news.csv` and run `Test_fine_tune_bert.ipynb`
