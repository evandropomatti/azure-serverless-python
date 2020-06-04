from mcr.microsoft.com/azure-functions/python:3.0-python3.8

COPY . /app
WORKDIR /app

RUN python -m pip install --upgrade pip setuptools wheel
RUN pip install -r requirements.txt