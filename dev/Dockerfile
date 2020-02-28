FROM python:3.7
FROM jupyter/minimal-notebook
WORKDIR /dev-base
RUN python -m pip install --upgrade pip
RUN python -m pip install jupyterthemes
RUN python -m pip  install --upgrade jupyterthemes
RUN python -m pip  install jupyter_contrib_nbextensions
RUN jupyter contrib nbextension install --user
COPY requirements.txt ./requirements.txt
RUN python -m pip  install -r requirements.txt


