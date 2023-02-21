---
title: "Spring 2023"
date: 2023-02-17T15:47:17-05:00
draft: false
---

Here you will find the full schedule of the Spring 2023 [VIDA Dataset Search and Discovery seminar]({{<relref "../">}}).

You can import the schedule to your own calendar using the following links:
  - [Google Calendar](https://calendar.google.com/calendar/embed?src=c_5be177770c1afa03d0162b1e565e674d5e6dcfee62b2338dcd6741b307a37510%40group.calendar.google.com&ctz=America%2FNew_York)
  - [iCal](https://calendar.google.com/calendar/ical/c_5be177770c1afa03d0162b1e565e674d5e6dcfee62b2338dcd6741b307a37510%40group.calendar.google.com/public/basic.ics)

<!-- https://calendar.google.com/calendar/u/0/r?cid=c_5be177770c1afa03d0162b1e565e674d5e6dcfee62b2338dcd6741b307a37510@group.calendar.google.com -->

## Schedule

| Date | Speaker | Talk | Location |
| ---- |-------- | ---- | -------- |
| 2/15 11am |Aécio Santos (_New York University_) | Sketching Methods for Efficient Correlated Dataset Search \[[Details](#aécio-santos-new-york-university)\] | (internal) |
| 3/01 11am |Natasha Noy (_Google Research_) | Google Dataset Search: Building an open ecosystem for dataset discovery \[[Details](#natasha-noy-google-research)\] | 370 Jay Street, Room 1201 |
| 3/17 11am |Raul Castro Fernandez (_University of Chicago_) | TBD \[[Details](#raul-castro-fernandez-university-of-chicago)\] |
| 3/24 11am |Fatemeh Nargesian (_University of Rochester_) | TBD \[[Details](#fatemeh-nargesian-university-of-rochester)\] |


## Talk Details

### Aécio Santos (New York University)

#### Abstract
Dataset search is emerging as a critical capability in both research and industry: it has spurred many novel applications such as data augmentation for enriching data analyses and improving machine learning models. In this talk, we present our recent work that explores a new class of dataset search queries that uncovers data relationships in large table collections. In particular, we focus on join-correlation queries: given an input query table, find the top-k tables that are both joinable with it and contain columns strongly correlated with a column in the query table. Unfortunately, a naïve approach to evaluate these queries, which first finds joinable tables and then explicitly materializes joins and computes correlations between the query and all discovered tables, is prohibitively expensive. To solve this problem, we 1) present novel data sketching methods that enable the construction of an index for a large number of tables and that provide accurate estimates for join-correlation queries, and 2) explore different indexing and scoring strategies that effectively retrieve and rank the query results based on how well the columns are correlated with the query.

#### Bio
Aécio Santos is a Research Engineer in the Visualization, Imaging, and Data Analysis (VIDA) group at New York University (NYU). He received a Master's Degree in Computer Science from the Federal University of Minas Gerais (in Brazil) and is currently a part-time Ph.D. candidate at New York University under the supervision of Prof. Juliana Freire. Over the years, he has worked, both in academia and industry, on a wide range of problems related to web crawling, news recommendation and classification, automated machine learning, and dataset search. He has served as a reviewer and has published papers at multiple premier data management and information retrieval conferences and journals such as VLDB, SIGMOD, WWW, WSDM, SIGIR, and CIKM.

### Natasha Noy (Google Research)

#### Location
370 Jay Street, Room #1201. Brooklyn, NY.

#### Abstract
There are thousands of data repositories on the Web, providing access to tens of millions of datasets. National and regional governments, scientific publishers and consortia, commercial data providers, and others publish data for fields ranging from social science to life science to high-energy physics to climate science and more. Access to this data is critical to facilitating reproducibility of research results, enabling scientists to build on others’ work, and providing data journalists easier access to information and its provenance. The talk will discuss Dataset Search by Google, which provides search capabilities over potentially all dataset repositories on the Web. I will talk about the open ecosystem for describing datasets that we hope to encourage. I will discuss what we have learned by analyzing the corpus of more than 45 million dataset descriptions. Finally, I will discuss research challenges in building a vibrant, heterogeneous, and open ecosystem where data becomes a first-class citizen.

#### Bio

Natasha Noy is a scientist at Google Research where she works on making structured data accessible and useful. She leads the team building Dataset Search, a search engine for all the datasets on the Web. Prior to joining Google, she worked at Stanford Center for Biomedical Informatics Research where she made major contributions in the areas of ontology development and alignment, and collaborative ontology engineering. Dr. Noy is a Fellow of the Association for the Advancement of Artificial Intelligence (AAAI). She has served as the President of the Semantic Web Science Association from 2011 to 2017.

### Raul Castro Fernandez (University of Chicago)

#### Abstract

TBD.

#### Bio

TBD.


### Fatemeh Nargesian (University of Rochester)

#### Abstract

TBD.

#### Bio

TBD.
