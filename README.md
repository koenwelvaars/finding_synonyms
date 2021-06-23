![alt text](https://i.imgflip.com/1ye64z.jpg)

# Searching for synonyms using text mining
This tool can be used to search clinical notes for similar words (i.e. synonyms). <br /> 
When you are looking for specific keywords in a clinical note, there will always be a different use of words within a group op physicians. For example: when looking for the word 'delirium', some physicians use this specific word. Other physicians might use words like 'forgetful', 'breakdown', and so on. To look up all these words that look/feel like 'delirium', we will use text mining and create insight in the differences in used terminology. <br /> 

This will be done using a word-matrix (Word2Vec), which calculates the probability of words that co-occur. The base assumption is that if words co-occur in a certain context, they will have a higher probability of having a similar meaning.
This is part of a bigger project, detection of complications in clinical notes, but is a fun way to get insight in usage of terminology.

Code can be found in:
- [Synoniemenzoeker](https://github.com/koenwelvaars/synoniemenzoeker/blob/master/code)

Info/suggestion? Feel free to contact me via k.welvaars@olvg.nl
