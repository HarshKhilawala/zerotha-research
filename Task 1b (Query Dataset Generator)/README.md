# LC-QuAD (Large Scale Complex Question Answering Dataset)
### Summary:
As the existing datasets were insufficient in terms of size and complexity to apply and evaluate the machine learning based question answering approach for 
learning complex SPARQL queries, the students and research group at university of Bonn provided the dataset with 5000 questions and their correspondent 
SPARQL queries over DBpedia dataset. This is the largest question answering dataset including complex questions followed by Free917 including 917 Questions 
and QALD-6 including 450 training questions and 100 test questions. 

Question answering approaches fall into two categories 
1.	Semantic parsing method which converts the Natural Language Query to an intermediate form, and then convert the intermediate form into logical form.
2.	Information retrieval method which converts the Natural Language Query directly into formal query language without converting into any intermediate form

But due to the limitation of size of Free917 and QALD-6 dataset, there was very little room for improvement in accuracy of employed ML techniques. 
In such scenarios, LC-QuAD Dataset addressed this question for the future publications of sementic parsing based approach.


Earlier, QALD Dataset was the only dataset based on DBpedia. LC-QuAD is around ten times larger as compared to QALD. 
But QALD Dataset is more complex and contains more informal and light conversation as its one created by the Domain experts as compared to LC-QuAD dataset 
which can be considered as one of its limitation but the questions included in the dataset resembles to the questions actually asked by any lively person. 
Apart from that, LC-QuAD Dataset has around 12.3 tokens for each question. 

Here is the table from the paper which compares the datasets and their corresponding logical forms:

| Dataset |	Size |	Entities |	Predicates |	Formal Language |
| :---: | :---: | :---: | :---: | :---: | 
| QALD-6 | 	450 |	383 | 378 | SPARQL |
| Free917 |	917 |	733 |	852 |	λ – Calculus|
| LC-QuAD |	5000 | 5042 |	615 |	SPARQL | 

LC-QuAD Dataset is easily available in form of JSON (JavaScript Object Notation) Dump. 
Such large dataset will be very useful in neural network based approaches for question answering as they can learn the human languages from scratch. 
