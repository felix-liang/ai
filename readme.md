## Install Python3.11  {.tabset .tabset-fade}

### Ubuntu

Clean up python:
```
sudo apt-get remove --auto-remove python3
```
Install Python 3.11
```
sudo apt install software-properties-common -y
sudo add-apt-repository ppa:deadsnakes/ppa -y
sudo apt update
sudo apt install python3.11 -y
```

## Set Default Python Version in Ubuntu
```
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.11 2
sudo update-alternatives --config python3
curl -sS https://bootstrap.pypa.io/get-pip.py | python3.9
```



## Install JupyterLab
```
pip install jupyterlab
```

## Install Tensorflow
```
pip install --upgrade pip setuptools wheel
python3 -m pip install tensorflow
```


## Start Jupyter Lab
```
jupyter lab --allow-root --ip=0.0.0.0 --no-browser
```
