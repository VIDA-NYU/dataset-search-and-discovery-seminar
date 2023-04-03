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
| 2/15 11:00am |Aécio Santos (_New York University_) | Sketching Methods for Efficient Correlated Dataset Search \[[Details](#aécio-santos-new-york-university)\] | (internal) |
| 3/01 11:00am |Natasha Noy (_Google Research_) | Google Dataset Search: Building an open ecosystem for dataset discovery \[[Details](#natasha-noy-google-research)\] | 370 Jay St, Room 1201 |
| 3/17 11:00am |Raul Castro Fernandez (_University of Chicago_) | System foundations of data markets and their connection to data discovery \[[Details](#raul-castro-fernandez-university-of-chicago)\] | 370 Jay St, Room 1114 |
| 3/24 12:15pm |Fatemeh Nargesian (_University of Rochester_) | Lakes of Data: From Semantic and Syntactic Dataset Discovery to Approximate Query Answering \[[Details](#fatemeh-nargesian-university-of-rochester)\] | 370 Jay St, Room 1113 |
| 4/7 11:00am |Laura Koesten (_University of Vienna_) | Data Discovery and Reuse: A Human-Centred View \[[Details](#laura-koesten-university-of-vienna)\] | Online via [Zoom](https://nyu.zoom.us/j/97184908181?pwd=R3NRWmI4YlZBQUJ4ZVZxV0wzbXJOQT09) |
| 4/14 11:30am |Ziawasch Abedjan (_Leibniz Universität Hannover, L3S Research Center_) | Data Discovery with Advanced Index Structures \[[Details](#ziawasch-abedjan-leibniz-universität-hannover-l3s-research-center)\] | TBD |
| 4/28 1:30pm |Asterios Katsifodimos (_Delft University of Technology_) | TBD \[[Details](#asterios-katsifodimos-delft-university-of-technology)\] | TBD |



## Upcoming Talks

### Laura Koesten (University of Vienna)

**Time:** April 7th, 2023. 11am.

**Location:** Online via Zoom: https://nyu.zoom.us/j/97184908181?pwd=R3NRWmI4YlZBQUJ4ZVZxV0wzbXJOQT09

**Title:** Data Discovery and Reuse: A Human-Centred View

**Abstract:** The web provides access to millions of datasets. These data can have additional impact when used beyond the context for which they were originally created. This is particularly relevant given the ever-increasing amounts of data being produced and made available and the creation of data-specific discovery tools and systems. Still, finding as well as reusing data remains challenging. While information-seeking in various settings has been well-researched within computer and information science, less is known about human-centered data discovery, or, in other words, how people discover, understand, and interact with data that others create. This talk will give an overview of research on how people evaluate and make sense of data they find and how data search systems and data repositories can be better designed to meet people’s needs.

**Bio:** Laura Koesten is a postdoctoral researcher at the University of Vienna in the Research Group for Visualization and Data Analysis and external researcher at King’s College London, UK. In her work, she is looking at ways to improve human-data interaction by studying sensemaking with data and visualisations, data discovery and reuse, as well as ethical and collaborative aspects of data-centric work. That means she researches how data is used, understood and presented by different user groups. She is PI of the Talking Charts project (https://talking-charts.vda.univie.ac.at/) and obtained her Ph.D. at the Open Data Institute + the University of Southampton, UK.


### Ziawasch Abedjan (Leibniz Universität Hannover, L3S Research Center)

**Time:** April 14th, 2023. 11:30am.

**Location:**  TBD.

**Title:** Data Discovery with Advanced Index Structures

**Abstract:** Data market places and data lake management are becoming more and more relevant in large organisations. One of the common use cases for using such data repositories is to obtain training data or features for a downstream machine learning (ML) task.
The goal is to enrich a given table with additional columns obtained from related tables that reside inside the data lake. Existing methods rely on the discovery of related tables that join on single attributes of a given table. However, many candidate tables that re discovered this way will only loosely be relevant for the given input dataset or might not contain additional interesting features. To further restrict the set of candidates complex filters based on multi-column matches and correlation calculation can be applied, which are time-consuming using state-of-the-art data structures and indexes. We have recently introduced two index structures that support multi-column join discovery and correlation calculation. In this talk, I will present these data structures and discuss the achieved performance on very large data lakes.

**Bio:** Ziawasch Abedjan is Professor for “Databases and Information Systems” at Leibniz Universität Hannover and Visiting Academic at Amazon Search. He is Junior Fellow of the German Computer Science Society, Fellow of the Berlin institute on Foundation of Learning and Data and member of the L3S Research Center. He has published more than 60 peer-reviewed papers in the area of data integration and data analytics. Ziawasch Abedjan received his PhD at the Hasso-Plattner-Institute in Potsdam and received the best dissertation award of the University of Potsdam in 2014. After his PhD, he was a postdoctoral associate at MIT and Junior Professor at the TU Berlin. He is further recipient of the SIGMOD 2019 most reproducible paper award, SIGMOD 2015 best demonstration award, and CIKM 2014 best student paper award. His research is funded by the German Research Foundation (DFG) and the German Ministry of Research and Education (BMBF).


### Asterios Katsifodimos (Delft University of Technology)

**Time:** April 28th, 2023. 1:30pm.

**Location:**  TBD.

**Title:**  TBD.

**Abstract:** TBD.

**Bio:** TDB.

## Past Talks

### Fatemeh Nargesian (University of Rochester)

**Time:** March 24th, 2023. 11am.

**Location:** 370 Jay Street, Room 1113.

**Title:** Lakes of Data: From Semantic and Syntactic Dataset Discovery to Approximate Query Answering

**Abstract:** The number and variety of structured data sources available on open data portals, the web, and data markets have been increasing rapidly, making secondary data analysis much more attractive. In fact, data scientists on many occasions may be spoiled for choice. In this talk, first, I will describe how we can push down syntactic and semantic join operations into dataset search to discover and infer queries for integrating data. Next, we will broaden the scope to query answering and see how to obtain an IID sample over the union of join queries, to perform approximate query answering. Finally, I will conclude by discussing the future directions in the distribution-aware aspects of integrating secondary data.

**Bio:** Fatemeh Nargesian is an assistant professor of computer science at the University of Rochester. She obtained her PhD at the University of Toronto. Her research interests are in data management for AI-based data analytics and scientific time-series management. Her work has appeared at top-tier venues including VLDB, SIGMOD, and ICDE, and has won the best demo award of VLDB 2017.

### Raul Castro Fernandez (University of Chicago)

**Time:** March 17th, 2023. 11am.

**Location:** 370 Jay Street, Room 1114

**Title:** System foundations of data markets and their connection to data discovery

**Abstract:** A data market is an environment where agents exchange data. From this "lens", many familiar scenarios can be considered data markets. When individuals give their data to online services in exchange for their services (think Google or Meta), they participate in a data market. Online marketplaces where companies trade data are a data market. And when employees of an organization exchange data with each other, they are participating in a data market. In this talk, I will first discuss the benefits of applying this "data market lens" to data environments. I will then present the work our group is doing in advancing this agenda, which roughly differentiates between a *data market design* and *data market platform implementation*. I will then concentrate on a novel platform we are building to support the implementation of data markets: a *data escrow*, a trustworthy third party that supports delegated and auditable computation, two ingredients necessary to implement data markets. Before concluding, I will present my view on how data discovery and data markets will lead to interesting new scenarios and applications.

**Bio:** I am interested in understanding the economics and value of data, including the potential of data markets to unlock that value. Our group builds systems to share, discover, prepare, integrate, and process data. We use techniques from data management, statistics, and machine learning. I am an assistant professor in the Computer Science department at the University of Chicago. Before UChicago, I did a postdoc at MIT with Sam Madden and Mike Stonebraker. And before that, I completed my PhD at Imperial College London with Peter Pietzuch.


### Natasha Noy (Google Research)

**Time:** March 1st, 2023. 11am.

**Location:** 370 Jay Street, Room #1201.

**Title:** Google Dataset Search: Building an open ecosystem for dataset discovery

**Abstract:** There are thousands of data repositories on the Web, providing access to tens of millions of datasets. National and regional governments, scientific publishers and consortia, commercial data providers, and others publish data for fields ranging from social science to life science to high-energy physics to climate science and more. Access to this data is critical to facilitating reproducibility of research results, enabling scientists to build on others’ work, and providing data journalists easier access to information and its provenance. The talk will discuss Dataset Search by Google, which provides search capabilities over potentially all dataset repositories on the Web. I will talk about the open ecosystem for describing datasets that we hope to encourage. I will discuss what we have learned by analyzing the corpus of more than 45 million dataset descriptions. Finally, I will discuss research challenges in building a vibrant, heterogeneous, and open ecosystem where data becomes a first-class citizen.

**Bio:** Natasha Noy is a scientist at Google Research where she works on making structured data accessible and useful. She leads the team building Dataset Search, a search engine for all the datasets on the Web. Prior to joining Google, she worked at Stanford Center for Biomedical Informatics Research where she made major contributions in the areas of ontology development and alignment, and collaborative ontology engineering. Dr. Noy is a Fellow of the Association for the Advancement of Artificial Intelligence (AAAI). She has served as the President of the Semantic Web Science Association from 2011 to 2017.


### Aécio Santos (New York University)
**Time:** February, 15th, 2023. 11am.

**Abstract:** Dataset search is emerging as a critical capability in both research and industry: it has spurred many novel applications such as data augmentation for enriching data analyses and improving machine learning models. In this talk, we present our recent work that explores a new class of dataset search queries that uncovers data relationships in large table collections. In particular, we focus on join-correlation queries: given an input query table, find the top-k tables that are both joinable with it and contain columns strongly correlated with a column in the query table. Unfortunately, a naïve approach to evaluate these queries, which first finds joinable tables and then explicitly materializes joins and computes correlations between the query and all discovered tables, is prohibitively expensive. To solve this problem, we 1) present novel data sketching methods that enable the construction of an index for a large number of tables and that provide accurate estimates for join-correlation queries, and 2) explore different indexing and scoring strategies that effectively retrieve and rank the query results based on how well the columns are correlated with the query.

**Bio:** Aécio Santos is a Research Engineer in the Visualization, Imaging, and Data Analysis (VIDA) group at New York University (NYU). He received a Master's Degree in Computer Science from the Federal University of Minas Gerais (in Brazil) and is currently a part-time Ph.D. candidate at New York University under the supervision of Prof. Juliana Freire. Over the years, he has worked, both in academia and industry, on a wide range of problems related to web crawling, news recommendation and classification, automated machine learning, and dataset search. He has served as a reviewer and has published papers at multiple premier data management and information retrieval conferences and journals such as VLDB, SIGMOD, WWW, WSDM, SIGIR, and CIKM.
