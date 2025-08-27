# IMC cell proximity analysis

This notebook is associated to the publication titled "Activated CD8+ T cells and macrophages form spatially organized niches that define chemotherapy response in breast cancer" by Sarkar et al. 

It loads some example data available within the repo, which are binary masks for different markers of interest obtained using Visiopharm on the Imaging Mass Cytometry (IMC) dataset [at this link]((https://www.ebi.ac.uk/biostudies/bioimages/studies/S-BIAD2027)). 

It then computes the minimum distance between cells positive to two different markers of interest.

# Set up

We recommend creating an environment (see [instructions here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#)) with the necessary packages as detailed below.

`numpy`
`matplotlib`
`scikit-image`
`pandas`
`seaborn`
`scipy`

When working with Jupyter notebooks, you will also need to install `jupyterlab` in the environment.
