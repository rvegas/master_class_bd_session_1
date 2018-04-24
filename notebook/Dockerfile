# Copyright (c) Jupyter Development Team.
# Distributed under the terms of the Modified BSD License.

# Pick your favorite docker-stacks image
FROM jupyter/base-notebook

USER jovyan

RUN pip install psycopg2
RUN pip install pymongo

USER root

ADD work /home/jovyan/work
