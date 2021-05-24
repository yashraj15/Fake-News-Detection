# Fake-News-Detection
Analyze knowledge graphs obtained from news resources for detection of fake news.


* We use a content-based approach, where we use the article to generate triples and, from these triples, extract information to identify fake news.

### Datasets Used
*  dEFEND dataset that was acquired from “politifact” and “gossipcop".

### Methodology
* We convert this data to triples using the Stanford OpenIE library, which is an NLP platform used to extract information and form relations within sentences. These triples are then stored in a CSV file.
* TransE model from `OpenKE` to train the datasets.

### Results
![image](https://user-images.githubusercontent.com/29776770/119370644-20aadd00-bc7b-11eb-9bea-3f20fccb5428.png)

### Conclusion
* The approach to the fake news detection was based on incomplete and imprecise knowledge of graphs and was based on the pre-existing TransE model. However, the results suggest that even incomplete knowledge can still detect fake news with decent accuracy. Unfortunately, our approach does not provide an explanation as to why the news were detected as fake.


