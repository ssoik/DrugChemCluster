# DrugChemCluster
Find and cluster analyze drugs chemically similar to a target drug.

Drug repurposing is an attractive alternative to traditional drug development, which is a very costly and time-consuming process. Here, I present hierarchical cluster analyses of all known drugs chemically similar to two common medications, Ibuprofen and Levothyroxine, as well as drugs similar to all approved Non-steroidal anti-inflammatory drugs (NSAIDs). Among these are experimental drugs, drugs with the same usage, and drugs with the opposite usage, suggesting that further analysis could predict the most (or least) effective drugs to repurpose for a target usage. Ultimately, this project aims to streamline the drug repurposing research process.

# Requirements
Python 3.7+

Pandas 0.25.3+

Numpy 1.18.1+

RDKit 2019.09.3+

Scipy 1.3.1+

MatPlotLib 3.1.1+

DrugBank All Structures dataset in CSV format (available at https://www.drugbank.ca/releases/latest#structures)

# Instructions
## X_clusters.ipynb
Set variable target_drug (dtype = str) to the exact DrugBank name for the drug of interest.

Set variable similarity_threshold [0 <= (dtype = float) <= 1] to desired chemical similarity threshold.

Run!
## X_category.ipynb
Set variable category (dtype = str) to the exact DrugBank category name of interest.

Set variable similarity_threshold [0 <= (dtype = float) <= 1] to desired chemical similarity threshold.

Run!
