# IssueSentimentTone

This repository includes the dataset, the data analysis code, and the complete results accompanying the paper published in CHASE2021, titled The Impacts of Sentiments and Tones in Community-Generated Issue Discussions.

Paper open access link:
https://arxiv.org/abs/2103.10615

For referencing the paper and/or the dataset:
- SANEI, A., CHENG, J. and ADAMS, B. (2021). The Impacts of Sentiments and Tones in Community-Generated Issue Discussions, in *Proceedings of the 14th International Conference on Cooperative and Human Aspects of Software Engineering, CHASE2021*.

## The dataset
The purpose of these artifacts is identifying the correlational impacts of sentiment and tone in issue discussions of three well-known Machine Learning GitHub repositories, Scikit-learn, PyTorch, and Tensorflow. There are embedded sentiment and tone in issues and comments.  We split our data into different categories such as issue length, issue poster, issue type, and commit size to investigate this correlation.

  - The "IssueData.csv" file contains information (including sentiments, tones, and the metadata) of all the issues and their comments of the three mentioned repositories.
  - The "ListOfAllCommitsPyTorch.csv" file contains all the PyTorch commits. 
  - The "ListOfAllCommitsSkLearn.csv" file contains all Scikit-Learn commits.
  - The "ListOfAllCommitsTensorflow.csv" file contains all Tensorflow's commits.

## The analysis code
  - The "SentimentToneAnalysis.ipynb" file is the Python code for analyzing the gathered data to indicate the impact of sentiment and tone on issue discussion and resolution time of the issue.
