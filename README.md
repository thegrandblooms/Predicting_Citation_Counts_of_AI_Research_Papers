# Predicting Citation Counts of Research Papers
### Using ROBERTA Document Embeddings and Linear Regression

In this quick notebook I show a Natural Language Processing and Machine Learning pipeline to predict 4.3% of variance (R2) in citation counts of research papers about Artificial Intelligence. This data is sourced from the 'aminer' database, and the papers analyzed are those that were presented through the International Joint Conference on Artificial Intelligence.

Linear Regression and XGBoost were benchmarked (without tuning), with Linear Regression outperforming. These results show that current NLP methods can explain some variance, but that research paper impact is likely the result of many factors, such as the structure of the academic graph, the institutions and researchers involved, the place of publication, the promotional efforts, and many other such factors not encompassed by the text in the abstract. Because of these systemic factors, improving citation prediction results will likely need to integrate data about these academic networks.
