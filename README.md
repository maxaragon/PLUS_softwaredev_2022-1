## PLUS_softwaredev_2022
Software dev practice course PLUS 2022 summer semester 
Course under copernicus masters program at university of salzburg

### create environment 
conda create --name geoenv gdal  ipykernel

### activate environment
conda activate geoenv

### export environment
conda env export > environment.yml

### export environment to requirments file
 conda list -e > requirments.txt
 
### making the environment available in Jupyternotebook
python -m ipykernel install --user --name=geoenv
