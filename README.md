# colab
Important note: in order to execute the notebook you need the following dependencies:
pandas, langdetect, python-Levenshtein, fuzzywuzzy

1) Cell 1: The user inserts time period to be searched in news and an entity to be searched for.
2) Cells 2-3: dependencies installation and importing
2) Cell 4 (run_search): This is the main function. It accepts time period and entity for search. Then it constructs the query for a GDELT table and executes it with pandas. GDELT stores the links and not the news content. So analyze_links is called
3) Cell 5 (utility functions): get_surrounding_sents is the summarization stub. It only takes a certain window of preceding and following the search query sentences. Get_text extract raw text from the GDELT link. 


