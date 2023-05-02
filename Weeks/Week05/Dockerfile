ARG BASE_CONTAINER=jupyter/scipy-notebook
FROM $BASE_CONTAINER

LABEL maintainer="Benjamin John Winjum <bwinjum@oarc.ucla.edu"

RUN conda install -c conda-forge py-xgboost && \
    pip install dtreeviz[xgboost]

COPY Week05_NB3_RandomForestXGBoost.ipynb /home/jovyan/Week05_NB3_RandomForestXGBoost.ipynb
