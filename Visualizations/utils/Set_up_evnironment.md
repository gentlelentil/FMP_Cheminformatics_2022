# create environment for FMP_Cheminformatics_2022 course

# create env
conda create python=3 -n FMP_Cheminformatics_2022

# activate env
conda activate FMP_Cheminformatics_2022

# install jupyterlab
conda install -c conda-forge jupyterlab

# install Kernel
python -m ipykernel install --user --name FMP_Cheminformatics_2022

# install packages
## essentials
conda install pandas
conda install numpy
pip install rdkit

## plotting
conda install -c conda-forge matplotlib
conda install seaborn
conda install -c plotly plotly=5.10.0

## dimensionality reduction
conda install -c conda-forge scikit-learn
conda install -c conda-forge umap-learn
