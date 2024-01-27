# webdata_collection_wordcloud

### Topic
the topic as well as the parameters you have used for search
### Parameters
Data was collected using search terms on YouTube. The following Python snippet shows the parameters used for searching New York:
```python
# The URL where the data will be collected from.
search_terms = ["career in new york", "settle in new york", "move to new york"]
for search_term in search_terms:
    url = "https://www.youtube.com/results?search_query=" + search_term.replace(" ", "+")
 ```
 Similar search terms were used for Boston and Seattle.

### Motivation for Comparison
why do you want to make this comparison


### Comparison of Word Clouds

![Boston Word Cloud](img/boston_wordcloud.png)
![New York Word Cloud](img/newyork_wordcloud.png)
![Seattle Word Cloud](img/seattle_wordcloud.png)

compare the word clouds and discuss the difference or similarity among the word clouds 
what might be the possible reasons for the patterns you observed
how your research could be improved in the future
compare with other content platforms
anything you find from the map or data that is different from your expectation before the exercise, or anything that stands out to you

**Result Spreadsheets:**
- [Boston csv file](assets/boston_dataset.csv)
- [New York csv file](assets/newyork_dataset.csv)
- [Seattle csv file](assets/seattle_dataset.csv)
