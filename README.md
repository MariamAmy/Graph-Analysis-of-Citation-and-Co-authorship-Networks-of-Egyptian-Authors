# Graph Analysis of Citation & Co-authorship Networks of Egyptian Authors

The study conducts a comprehensive analysis of citation networks focusing on publications by authors affiliated with Egyptian institutions. Leveraging the Semantic Scholar platform and its API, a citation network ana a co-authoship network graphs are constructed to visualize the interconnections among these publications and their authors mainly using the python package for graph analysis (Networkx). The primary objective is to identify influential Egyptian publications and assess the centrality of nodes within the citation network. Te findings provide valuable information on the impact of Egyptian publications, offering insights into the scholarly influence of authors associated with Egyptian institutions. This research equips researchers and academics interested in evaluating the impact of Egyptian publications with valuable data for future studies, collaborations, and policy decisions.


## Dataset [AlGoNet]
Data of egyptian papers was collected by sending API requests to semantic scholar website using the API key for a higher requests rate. There are wo main stages:

#### 1. Webscrabing Google Scholar:
+ Dataset provides details about the researchers' names and affiliations.
+ The dataset comprises information on 13,027 researchers, including both Egyptians and individuals affiliated with Egyptian universities.
+ Scraping was done using Python library Selenium.
+ Data collected on researchers affiliated with the following universities: Ain Shams University, Cairo University, EJUST University, Alexandria University, Banha University, Assiut University, and Zewail University.   

#### 2. Data of those authors' papers using Semantic Scholar API:
+ Final dataset: 31,508 research papers.
+ Each paper includes at least one researcher from Egypt or affiliated with an Egyptian university.
+ Paper details: title, unique paper ID, publication year, and a list of authors' names, IDs in semantic scholar, citation count and a list of all references titles and corresponding IDs for each.

+ API Requests Limitations:
  + The Semantic Scholar API key allows a request rate of 100 requests per second.
  + The API returns a maximum of 500 authors' data for each paper.
  + The API returns a maximum of 1000 references for each paper.
+ [Check any updated info regarding semantic scholar API requests](https://api.semanticscholar.org/api-docs?utm_medium=email&_hsmi=230452164&_hsenc=p2ANqtz-_qqTwwj9_nmTTO1Rgps8SST_95rgUi3jjt4VxwQ6BOaFkEntuUMB8csVGToUyoMQSRQzZT6HYiybCLxIdnx3v4VVoIhA&utm_content=230452164&utm_source=hs_automation)


The following studies were conducted and illustrated in our paper:
## Analysis of Citation Network
#### 1. Temporal Analysis of Publications
#### 2. Degree Distribution Analysis
#### 3. Authorship Pattern Analysis
#### 4. Clustering Coefficients
#### 5. Density Analysis
#### 6. Centrality Measures
  + Average Degree Centrality for the all collected paper
  + Degree Centrality for Publications (>2015)
  + Eigenvector Centrality for Publications (>2015)
#### 7. Strongly Connected Components

## Analysis of Co-authorship Network
#### 1. Degree Centrality Measures
#### 2. onnected Components Analysis


## Acknowledgments
We would like to express our deepest gratitude to Eng. Zeyad Shokry for his invaluable guidance and assistance with the collection of the dataset.

## Contributors
[ <a href="https://github.com/MariamAmy">Mariam Ayman</a> -  <a href="https://github.com/SohailaKandil">Sohaila Kandil</a> - <a href="https://github.com/youssef-elharty">Youssef El-harty</a> - <a href="https://github.com/ahmedhjaj/">Ahmed Hagag</a> - <a href="https://github.com/ProbablyOmar">Omar Wassim</a> - <a href="https://github.com/alaaamoheb">Alaa Moheb</a>]

## License  
Self-citation analysis data based on PubMed Central subset (2002-2005) by Shubhanshu Mishra, Brent D. Fegley, Jana Diesner, and Vetle Torvik is licensed under a Creative Commons Attribution 4.0 International License. Permissions beyond the scope of this license may be available at https://github.com/napsternxg/PubMed_SelfCitationAnalysis.
