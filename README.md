# LM_Personalization
About Codebase for "PRIME: Language Model Personalization with Cognitive Memory and Thought Processes"


## Data: CMV

The **CMV** dataset is available at [data](./data) directory. The original raw data is crawled from the [Academic Torrents website](https://academictorrents.com/details/20520c420c6c846f555523babc8c059e9daa8fc5/).


The folder structure of the [CMV dataset](./data) is as follows:
```
data/
├── history_data.json # Contains the history engagements from 2013 to 2022. One engagement is a linearized conversation between the post author and one or more commenters. 
├── evaluation_data.json # Contains 133 user queries (2023-2024) used for evaluation.
└── target_authors_collection.json # Contains a set of 41 *active* target authors studied in this work. Refer to the paper for more details (Section 3 and Appendix C).
```

*Note*: The `history_data.json` file contains history conversations published by authors more than those in the `target_authors_collection.json`. Please use the `target_authors_collection.json` to filter in the conversations of the target authors.

## Framework: PRIME
*We are still refactoring and cleaning the codebase, Please stay tuned for more updates.*

