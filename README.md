# Notebook Archaeology

  Data and information related to the paper "Notebook Archaeology: Inferring Provenance from Computational Notebooks" (IPAW 2021). Our goal was to infer provenance information about how Jupyter notebooks were created and executed based on the final state of the notebook, saved as an ipynb file. To do this, we analyzed patterns in Jupyter (Python 3) notebooks and IPython session histories. Using that information, we created an algorithm that fills in missing gaps in the execution history with possible events, finding it challenging since we lack many details including which cells may have been executed multiple times or were deleted.

[Paper](https://doi.org/10.1007/978-3-030-80960-7_7)

## Data:
* [Sampled Notebooks & Session Histories](https://zenodo.org/record/5113980#.YPWoPS1h1yo): The 100,000 notebooks sampled from GitHub and the 646 history.sqlite files containing 86,711 sessions, also downloaded from GitHub. Note that outputs have been stripped from notebooks, and some notebooks and session histories are  invalid.
