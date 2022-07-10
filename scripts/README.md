## Description

This folder contains all the scripts for the mining, analysis and visualization of the data sets.

## Contents

- [analysis/](analysis/)
  - [Commit_analysis.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/analysis/Commit_analysis.ipynb) -->  This notebook contains python code to transform the RAW JSON commits data into CSV format, calculate statistics about the labels and visualize them.
  - [Issues_analysis.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/analysis/Issues_analysis.ipynb) -->  This notebook contains python code to transform the RAW JSON issues data into CSV format, calculate statistics about the labels and visualize them.      
- [mining/](mining/)
  - [commit_mining.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/mining/commit_mining.ipynb) --> This notebook contains python code that makes use of [PyDriller](https://pydriller.readthedocs.io/en/latest/commit.html) to mine commit data from relevant repositories.    
  - [issue_mining.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/mining/issue_mining.ipynb) --> This notebook contains python code that makes use of [Perceval](https://pypi.org/project/perceval/) to mine issue data from relevant repositories.
  - [repository_mining.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/mining/repository_mining.ipynb) --> This notebook contains python code that makes use of [PyGitHub](https://pypi.org/project/PyGithub/) to retrieve the links of the repositories that use Terraform as their cloud orchestrator.  
- [nlp/](nlp/)
  - [Sentiment_analysis_commits.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/nlp/Sentiment_analysis_commits.ipynb) --> This notebook contains the python code needed to re-run the sentiment analysis experiments using [Stanza](https://stanfordnlp.github.io/stanza/sentiment.html), [TextBlob](https://textblob.readthedocs.io/en/dev/quickstart.html), and [Vader](https://github.com/cjhutto/vaderSentiment) on commits data.
  - [Sentiment_analysis_issues.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/nlp/Sentiment_analysis_issues.ipynb) --> Same as above, but for issue tracker data.
  - [topic_modeling_commits.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/nlp/topic_modeling_commits.ipynb) --> This notebook contains the python code needed to re-run the topic modeling experiments using [Stanza](https://stanfordnlp.github.io/stanza/) and [Gensim](https://radimrehurek.com/gensim/) on commits data.
  - [topic_modeling_issues.ipynb](https://github.com/Max593/Mining-and-Analysis-of-Cost-related-Decisions-in-Cloud-Infrastructures/blob/main/scripts/nlp/topic_modeling_issues.ipynb) --> Same as above, but for issue tracker data.      
