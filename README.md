# earth_engine_mapping
## Set up a conda environment
conda create -n geo python=3.8
conda activate geo
conda install geemap -c conda-forge
conda install jupyter_contrib_nbextensions -c conda-forge
jupyter contrib nbextension install --user
