# Identifying-AMP-and-their-function-types-using-Machine-Learning

Part 1:
Dataset - Part1Features.arff <br>
Jupyter Notebook - Part 1 Classifier.ipynb

Part 2:
Developed using MEKA <br>
Evalutaion Metrics - Meka Evaluation Info.txt

**CSI 5180. Topics in Artificial Intelligence**

**Machine Learning for Bioinformatics Applications**

**Topic**

An advanced approach to identify antimicrobial peptides and their function types for penaeus through machine learning strategies. BMC Bioinformatics, 20(Suppl 8):291, Jun 2019.

[https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6557738/pdf/12859\_2019\_Article\_2766.pdf](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6557738/pdf/12859_2019_Article_2766.pdf)

**Abstract**

Antimicrobial peptides (AMPs) are essential components of the innate immune system and can protect the host from various pathogenic bacteria. The marine environment is known to be one of the richest sources for AMPs. Effective usage of AMPs and their derivatives can greatly improve the immunity and breeding survival rate of aquatic products. It is highly desirable to develop computational tools for rapidly and accurately identifying AMPs and their functional types, for the purpose of helping design new and more effective antimicrobial agents.

The paper talks about two models; first one to classify whether a sequence is AMP or Non-AMP (Binary Classifier) and the second model further takes the AMP sequences to classify them as per there activity (Multi Label Classification).


**Dataset**

The data is extracted from APD database which comprise of AMP and Non-AMP sequences. The extracted features are 188D with labels as -1 and 1 indicating AMP / Non-AMP sequence.

In total we have 6989 instances with 2618 as AMPs and 4371 as Non-AMPs. This will be used for our training and testing purpose. We would be using sampling techniques to address the data imbalance problem.



**Project Plan**

Below is the scope and proposed plan for the project.

1. Use the extracted features; the paper has a link for the features being used for models.
2. Perform sampling techniques (Under sampling)
3. I also plan to try the oversampling technique (SMOTE) for the first model and its impact on the model&#39;s performance.
4. As there are not many details on the test dataset extraction, I plan to use the 70:30 technique on the training dataset.
5. Apply Random Forest and a new model to classify the sequence as AMP or Non-AMP. [Binary Classification]
6. Performance Evaluation.
7. Implement the second classifier; apply Random Forest for Multi-label classification using MEKA.

