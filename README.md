This GitHub repository contains code for performing topic modeling on arXiv abstracts using the dataset provided by Hugging Face Datasets, which can be downloaded here:

https://huggingface.co/datasets/gfissore/arxiv-abstracts-2021/viewer/default/train?p=19994

The code focuses on text analysis and topic modeling with a multi-faceted approach. It begins with data preprocessing, involving cleaning steps and keyword matching for relevant content extraction. Subsequently, the script employs Latent Dirichlet Allocation (LDA) for topic modeling, identifying latent topics within the text corpus. Additionally, K-Means clustering is utilized to group related documents.

For a more granular analysis, a Sentence-Level Transformer is implemented, capturing nuanced information within individual sentences. This enhances the model's ability to discern context at a finer level.

Prior to the modeling stages, the script conducts word frequency analysis to identify prominent terms. Temporal analysis is performed to discern trends and patterns over time.

The comprehensive approach not only uncovers overarching themes through LDA and K-Means but also captures subtle nuances using Sentence-Level Transformer. Cleaning and keyword matching ensure that the analysis is focused on relevant information. Word frequency and temporal analyses add depth to the understanding of the dataset.
