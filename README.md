# Gender difference on happy moments

This project is based on an crowd-sourced dataset [HappyDB](https://rit-public.github.io/HappyDB/). Generally, it helps answer the following questions in order to get some insights of the gender difference on happy moments:

```
The data file is stored the data used in the project.
The doc file is stored the code used in the project.
```


## Question 1: What's the difference of the words in each gender group?

Both male and female like use nouns, verbs and adjs to express the happy moments. The top 10 words of frequency in each groups also support the notation. Women have 8 nouns and 2 verbs and man have 7 nouns, 2 verbs and 1 adverb(finally).

Also, we can find that both women and men are enjoyed the happy moments with their friends. But women tend to be more bond with people around them for the words like husband, daughter, son, family come up more frequently than men's. 


## Question 2: What's the difference of the periods in each gender group?

For both female and male, there is no difference in the total number of the reflection period. But with the content of each period, female and male show differently.

Since the p-values of Kolmogorov-Smirnov test are very close to 1, the null hypothesis cannot be rejected at 0.01 significance which means there is no statistically difference between the POS of 24 hours and that of 3 months in each gender group.

After removing the most frequently used words in each group, the results show that in 24-hour's memory, women have more 'fleeting' words - words describing movement, such as watched, feel, enjoy, ect. In 3-month's memory, women have more nouns describing the person they shared the happy moments with. This is compatible with the memory loss. But focusing on men's words in different reflection period, the POS of the words seem remain.


## Question 3: Get Sentiment

Both female and male use more positive words than negative words to express their happy moments. For the sense of words, the words which show joy and anticipation are more likely used for happy moments. The histogram shows both mean of the sentiment values are concerntrated on 0. Under the ks.test, there is no significantly difference between the sense used by women and that by man. 

## Summary
From the analysis above, we can firstly know that the happy moments are mostly postive which is confirmed with the name of the research 'Happy Moments'. Both women and men used nouns, verbs and adjectives to express their happy moments. Besides, women like to remember the people who spent the happy moments with them but men don't show the tendency.

There is no statistically difference between the numbers of happy moments of different period in each gender group.But the content of the word used by females and males show difference. Women tends to use verbs or adjectives to describe their happy moment in short-term memories, more nouns for discription in longer-term memories while men don't show the same tendency.
