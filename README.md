# FinNum: A Financial Numeral Understanding Dataset for Financial Social Media Data
# Introduction
Numeral is the crucial part of financial documents. In order to understand the detail of opinions in financial documents, we should not only analyze the text, but also need to assay the numeric information in depth. Because of the informal writing style, analyzing social media data is more challenging than analyzing news and official documents. FinNum is a dataset for fine-grained numeral understanding in financial social media data - to identify the category of a numeral.

# Format
In provided dataset, participants will get "idx" (the index of the tweet), "id" (the id of the tweet), "target_num" (the target numeral), "category" (annotated result), "subcategory" (annotated result), and should rebuild the data via Stocktwits API. Note that, three categories (Indicator, Quantity, and Product/ Version number) do not have subcategory. Thus, the category and subcategory information are the same for these three categories.

# Example

```yaml
[{

'idx': 7791,

'id': 100382304,

'target_num': ['10'],

'category': ['Monetary'],

'subcategory': ['forecast'],

'tweet': '$FLKS Cantor Fitzgerald reiterates Hold rating, $10 PT =&gt; https://stocknews.com/news/flks-cantor-fitzgerald-reiterates-hold-rating-10-pt/ #FlexPharma #Biotechnology #BioTech #Bullish #Stock #FLKS'

},

{

'idx': 5720,

'id': 102960935,

'target_num': ['28', '2017'],

'category': ['Temporal', 'Temporal'],

'subcategory': ['date', 'date'],

'tweet': '$BTL BTL - Upward momentum Long from $8.70 or $8.05 . \n* Trade Criteria * \nDate First Found- November 28, 2017\nPattern/'

}]
```
# Download
Download ```FinNum.zip``` for the data.

# How to Cite the Corpus
Please cite the following paper when referring to the FinNum in academic publications and papers.

Chung-Chi Chen, Hen-Hsen Huang, Yow-Ting Shiue, and Hsin-Hsi Chen. 2018. [Numeral Understanding in Financial Tweets for Fine-grained Crowd-based Forecasting](https://ieeexplore.ieee.org/abstract/document/8609586). In Proceedings of the 2018 IEEE/WIC/ACM International Conference on Web Intelligence (WI 2018), Santiago, Chile.
# License
FinNum is licensed under the Creative Commons Attribution-Non-Commercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) license.
