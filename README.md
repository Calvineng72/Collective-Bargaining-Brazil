# Decoding Collective Bargaining in Brazil: A Study of Textual Predictors for Agreement Approval
### Author: Calvin Eng
Link to Paper-
https://drive.google.com/file/d/1vpAhWOA3z8B3cCIEi4IhvejupZmTWIsh/view?usp=sharing
## Project Details
The following project seeks to analyze collective bargaining agreements to determine what makes a document gain approval. Using a corpus of CBAs derived from Brazil in the year 2009, the project uses text analysis techniques, such as TFIDF and lemmatization, alongside logistic regressions with and without penalty terms to determine what correlates with the approval of collective bargaining agreements. The paper analyzes clause counts and word choice as independent variables, seeking to find evidence for correlations with validity. For the corpus used in the research, please contact me at calvin_eng@brown.edu, as there are too many documents to be added to Github.
## Research Question
What textual variables that can be extracted from collective bargaining agreements are correlated with their validity?
## Data
The data is derived from a collection of CBAs from Brazil from 2008-2017, focusing on the year 2009. The agreements contain information such as the employer, the union, the number of union representatives, whether the document is valid, whether it has been amended, the date negotiated, the date the agreement takes effect, and a variety of clauses on topics like minimum wage, overtime pay, hazard pay, night pay, seniority pay, childcare assistance, maternity assistance, hiring rules, female workforce, vocational training, equal opportunity, etc. Only documents containing more than two clauses and negotiated between firms and their employees are considered. The corpus used in the research amasses 38401 documents.
## Method
The project uses lemmatization and TFIDF for text analysis, while most regression analysis is done with logistic regressions with an L1 penalty term. 
## Results
The paper finds no correlation between the number of clauses, word choice, and document validity. However, further research into the structural composition, word choice, and syntax of collective bargaining documents should not be overlooked.
## Replication Instructions
In order to clone the repository to view the code, run the following in the terminal. 
    
    git clone https://github.com/Econ1680-MLTAEcon-Handlan/project-2-Calvineng72.git
