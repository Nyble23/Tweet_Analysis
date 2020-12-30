# Tweet_Analysis

### What is this code about?
This is small analysis of tweets collected on a particular day in June,2020. In India, during this time, 2 hashtags were trending:
- #RestInPeace
- #MissYouYuvi

#RestInPeace was mostly being used in woke of Coronavirus death and #MissYouYuvi for Yuvraj Singh. There was a cross-over between both the hashtags. The main goal was to study ana analyse cross-over between the these two hashtags.

### Dataset
The associated tweets can be found in the dataset present in the repository. Tweets are present in JSON format.

### Methodology
1. The tweets were divided into 3 main categories : #MissYouYuvi only, #RestInPeace only, Both #RestInPeace and #MissYouYuvi
2. The 3 Tweets set were considered as 3 classes: Class A, B, C respectively and then analysis was done.

### Findings
- Number of tweets that fall in the 3 classes.
- Number of users who were tweeting about each class.
- Number of verified and not verified users.
- Topic Modelling on the three classes.
- With respect to the Tweets for #RestInPeace, location information from the meta-data of tweet was identified, and it was verified whether the number of deaths in a location is correlated to the number of cases in the region. ( Number of cases in a region were pulled out from this [source](https://www.covid19india.org/)).

***The Python Notebook can be used as a reference to understand how raw tweets can be used to bring out meaningful outcomes.***
