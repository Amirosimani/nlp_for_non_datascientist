# NLP for All - Event Detection

The amount of text data available is mind-boggling. We will explore programatic approaches to identify information about what happened and when it happened by gathering knowledge from text.


## Installation

`pip install -r requirments.txt`


`python -m spacy download en_core_web_lg`


https://spacy.io/usage/models


## Start a notebook on Docker

`docker run --rm -p 10010:8888 -e JUPYTER_ENABLE_LAB=yes --name nlp -v %cd%:/home/jovyan/work  jupyter/tensorflow-notebook:latest`