# The Language of Game of Thrones
## Project 5: The Language of Game of Thrones: A Dissection of Character Agency and Dialogue by Gender  

Guide to Notebooks Folder:
* Each season has its own Jupyter notebooks that involves: Getting the scripts for each episode, breaking up the scripts by dialogue, breaking up the dialogue by character, repeating for each episode, and joining together to create a whole season. 
* The Word2Vec Jupyter notebook involves: Importing and cleaning my episodes and dialogue corpus, deciding on key characters to focus on, creating a dataframe for each season where each row is a key character's dialogue, constructing a Word2Vec model, using Word2Vec’s similarity score function that would find a score for how similar each line of dialogue was to a key agency word, and then tracked that on a season by season basis to track agency over time.
* The t-SNE Jupyter notebook involves: Building a t-SNE in order to visualize my higher dimensional Word2Vec model, running PCA in order to bring the 100-dimensional Word2Vec to 20 dimensions, running t-SNE in order to bring the 20-dimensional PCA resutls to a 2-dimensional visualization. 
* The sentiment analysis Jupyter notebook involves: Importing and cleaning my episodes and dialogue corpus, creating a dataframe for each season where each row is a key character's dialogue, constructing a sentiment analysis function that would find a sentiment score for each line of dialogue, and then tracked that on a season by season basis to find sentiment analysis of character dialogue over time.
