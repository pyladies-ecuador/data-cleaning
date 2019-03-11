# Data cleaning with Jupyter Notebook, Pandas

<img src="https://raw.githubusercontent.com/pyladies-ecuador/pyladies-ec-kit/master/assets/logos/logo-map-ec.jpg" height="200"> 

## Evento 
* 2019-03-09: **"por Limpieza de datos con Pandas"**, por Gabriela Guamán y Silvia Vacacela | [Evento](https://www.meetup.com/pyladiesEc/events/259074450/)

## Presentación
* 2019-03-09: **"PDF"**,  por Gabriela Guamán  | [File](url tiene que estar dendro del mismo proyecto de git)
* 2019-03-09: **"POWER POINT"**, por  por Gabriela Guamán  | [File](url tiene que estar dendro del mismo proyecto de git)

## PyLadiesEc March meetup 2019
## Installation: the environment
Simple instructions to start a Jupyter notebook using a virtualenv environment in Python 3.

### If pip3 is not installed, install it
sudo apt-get install python3-pip

### Upgrade
pip3 install --upgrade pip

### If virtualenv is not installed, install it
### Feel free to use either pip or pip3, doesn't matter
pip install virtualenv

### Move to the folder and create the virtualenv
virtualenv -p python3 dataCleaning

### Activate the virtualenv
source dataCleaning/bin/activate

### Install Jupyter, Pandas, Plotly and Matplotlib
pip3 install jupyter pandas plotly matplotlib requests

### Start the notebook server (from withing the folder with the virtualenv folder)
jupyter notebook

### Open a new notebook from the top-right button "New"
