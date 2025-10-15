# Data analytics with Python and AI

## What is it?
This project contains files to analyze weather data with Python and AI.

## Where to get it
The source code is currently hosted on GitHub at:
https://github.com/c4ristian/wetter

## Data source
Analysis is performed on weather data from the German Weather Service (DWD).
https://opendata.dwd.de/climate_environment/CDC/

## Setup
```sh
conda env create -f environment.yml

conda activate assc
```

## Jupyter

### Install Kernel 
```sh
python -m ipykernel install --user --name=wetter
```

### Run Notebooks
```sh
jupyter notebook --notebook-dir="./notebooks"
```

## License
[Apache 2.0](LICENSE.txt)


## Contact
[christian.koch@th-nuernberg.de](mailto:christian.koch@th-nuernberg.de)