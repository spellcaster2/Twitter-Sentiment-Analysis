# Twitter-Sentiment-Analysis
The goal of the project is to analyse the tweets of people and classify them as positive or negative.

Techniques used in project

1) Stemming
“Stemming is process of reducing infected or derived words to their word stem, base or root form”
Example:- intelligence, intelligent, intelligently all are converted into intelligen.
Problem:
Produced intermediate representation of the word may not have any meaning. 
Example: intelligen, fina etc

2) Lemmatization
Same as Stemming but intermediate representation/root form has a meaning.
Example:- intelligence, intelligent, intelligently all are converted into intelligent.

Bag Of Words –Problems
1)All words have the same importance.
2)No semantic information preserved.

TF-IDF Model –The Solution
1)Some semantic information is preserved as uncommon words are given more importance than common words.
Example: ‘She is beautiful’. Here ‘beautiful’ will have more importance than ‘She’ or ‘is’.

𝑇𝐹𝐼𝐷𝐹𝑊𝑜𝑟𝑑=𝑇𝐹𝐷𝑜𝑐𝑢𝑚𝑒𝑛𝑡,𝑊𝑜𝑟𝑑∗𝐼𝐷𝐹(𝑊𝑜𝑟𝑑)

N-Gram Modelling 
“An N-gram is a contiguous sequence of n items from a given sample of text or speech” 
Items refer to states in Markov Chains
Items can be “characters”, ”words”, “sentences” etc.
