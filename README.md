# data-eng

## Data Crunching -- Panama Papers
> Data source: http://ckan.initiumlab.com/dataset/panama-leaks

### Question list:

* Conduct a pilot study on this dataset
  * Basic information
  * Size of tables
  * Interpretation of table columns
  * What do you think might be interesting?
  * Propose some questions to be answer by data mining on this data set.
* Potential questions:
  * Visualise the geo-distribution of intermediaries, holders, etc
  * Visualise the time series of company setup/ termination.
  
## Data Crunching -- theinitium.com articles

### Task list:

* Scrape this channel (or another one): https://theinitium.com/channel/hongkong/ . Get structured article list data
* Handle pagination to scrape the whole list of articles
* Answer the following questions:
  * How many articles do we generate each week in this channel?
  * What is the distribution of article title lengths?
  * What is the most frequent keywords in title/ summary?
  * What is the distribution of cover image file sizes?
* For each article in the list, scrape the article page and get detailed information: title, description, date, author, tags, related articles
* Answer the following questions
  * Which month/week do we have the largest number of publications in this channel?
  * Who are the top 5 authors in terms of number of articles?
* Entity extraction:
  * Use any libraries to extract entities: paragraph, figure, heading, number, wiki, etc
  * What are the most commonly used entities?
* Make a tag cloud for this channel

Homework:

* Scrape all the channels and all the articles
* Visualize the relationship between articles using a graph (Treat related articles as the citation)

> Memo: No need to finish all the questions in one interview. The interviewer can add/remove questions in the process.

#### Sample article list data:

```
 [ 
   {
     "title": "雨伞与旺角后，直击2016立法会选举",
     "url": "http://project.initiumlab.com/legco-election-2016/"
  },
  {
     "title": "在香港最高大厦幕墙，倒数2047",
     "url": "/article/20160518-hongkong-2047/"
   },
  ...
 ]
 ```
