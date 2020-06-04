
## Getting started

To activate the virtual environment

```sh
apt-get install python3-venv
python3 -m venv .venv
source .venv/bin/activate
pip3 install opencv-python
```

To add a depency run `pipenv install`:

```sh
pipenv install opencv-python
```

```
sudo docker build -t <image_name> .
```

Make sure the pipenv matches the python version

## Choosing a base image

Microsoft 

https://github.com/azure/azure-functions-docker#python

https://github.com/Azure/azure-functions-docker#python


https://github.com/evandropomatti/install-pipenv-ubuntu

## Sending my image to the cloud

Use a pipeline to build and push the image to a repository.