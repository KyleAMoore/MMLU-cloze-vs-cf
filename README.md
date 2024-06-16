# The Base-Rate Effect on LLM Benchmark Performance
This repository holds the code necessary for the replication of our experiments and data analysis used in the paper "The Base-Rate Effect on LLM Benchmark Performance: Disambiguating Test-Taking Strategies from Benchmark Performance". This paper is currently under review.

### Dependencies

#### PopulationLM
Our code uses an inference pipeline that is dependent on a tool previously created by our research group called PopulationLM. This tool is used to generate a "population" of language models for behavioral study. No results from populations were used in this paper, but the dependency is maintained. The code for PopulationLM can be found here: https://github.com/JesseTNRoberts/PopulationLM

#### Minicons
Minicons is a library (orginally found here: https://github.com/kanishkamisra/minicons) that gathers probability and probability distribution data for multi-token sequences in language models. Our experiments rely on extensions made to this library to handle cloze testing and more robust model loading. To replicate our results, you should install the version of Minicons found here: https://github.com/JesseTNRoberts/minicons_modded

#### Other libraries used
matplotlib
numpy
pandas
plotly
researchpy
seaborn
torch
transformers
tqdm

#### Architecture
All experiments were performed in Google Colab using an A100 - High RAM environment. Data analysis was performed in a CPU only environment on Google Colab.
