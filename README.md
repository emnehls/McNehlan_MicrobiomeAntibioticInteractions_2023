# Machine learning to study microbiome-antibiotic interactions in neonates

This repository is an exploration of the interaction between neonatal microbiome content
and antibiotic therapy in determining infection outcomes.

The data contains sequencing information about microbiome content of neonates,
information about which antibiotics were administered,
and information about infection outcomes.
Additionally, there are other clinical and microbial characteristics,
including information on antibiotic resistance and reads that 
could contain information about microbial virulence factors.

An initial plan is to use machine learning to classify disease outcome
based on the input info on microbiome content and antibiotic treatment.
The eventual goal would be to use microbiome content to identify the 
proper antibiotic regimen that would result in positive outcome. 

In order to approach this, 
I first need to learn about machine learning algorithms and how to implement them.

## Notes on machine learning algorithms

- There are many!
- Broadly categorized into supervised (where features and labels of the training set are known) and unsupervised (where only features of training data are known)
    - The data we have is fully labeled - I know the disease outcome of every patient in the training dataset
    - I will likely use a supervised algorithm to classify disease outcome (label) based on input features
- Simplest supervised algorithm is k-means
- SVM seems like a highly tractable approach for this type of problem

## Notes on organization

- I have a zotero library in my library for this project
- All of my progress will be under version control via Github
    - I will make this a public repository with an MIT license from the start as long as the data is public
- I will need to document everything super well, as I will be doing this as a side project during medical school and will likely have long stretches when I'm not thinking about it at all

