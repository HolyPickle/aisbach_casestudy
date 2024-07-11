# Aisbach Coding Tasks

## Results
<b>Final results can be inspected from the final_results.csv file</b>

### Steps:
1. Check company websites for information about whether they are investing in solarparks.
2. Check Google News with Selenium for news articles from different websites. Title and short description are available alongside with source, link, and date
   1. Rule-Based labeling based on title and description
   2. NLP-Based labeling with SpaCy based on title and description
3. Gather further information about parsed news articles with using newspaper3k and links from google news.
   1. NLP-Based labeling with gathered article data from different news websites
   2. If detailed article is not available or non-relevant, use desc
4. Analyse the results
   1. Extract investment amounts
   2. Extract generated enery amounts
5. Aggregate results -- not completed


## Future Work
* Some articles are in German, NLP solution can be applied for different languages or gathering only the English ones
* Gathered article information from publisher websites can be cleaned. 
* We can convert all investment and generated energy amount findings into numberical values and aggregate them to derive a final number for both inversment amount and generated energy
* This numbers will not be reliable but can be useful to have an idea
* For the labels for whether if companies are investing in solarparks, we can just take the max
* LLMs can be used to extract more relevant information from data.
* For LLM use, one-shot prompting can be useful to extract just the data needed.


## Notes
* Due to my exams I cannot spend more time on this task. Therefore aggregation part is not complete
* Results still can be inspected manually from the final_results.csv file
* Overall, I really enjoyed tyring to solve this challenge. When it comes to data scraping possibilities and tools are almost endless :)
* I tried a lot of methods to get away just with HTMP parsing but Google didn't let me get away with it. I am not sure why. :/
* Event though I wasn't able to use LLMs because of my time limitations, rule-based approach seems to work just fine while being computationally cheaper.


## Disclaimer
* Regex is hard, so I used ChatGPT to generate them. :)
  