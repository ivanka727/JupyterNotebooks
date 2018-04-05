FROM jupyter/scipy-notebook
USER root
RUN conda install --yes --name root psycopg2
<<<<<<< HEAD
RUN conda install --yes --name root redis rq 
=======
RUN conda install --yes --name root redis rq
>>>>>>> ae712c6dc7513a31cb5a47d30bf349a1f5ddf3f9
RUN conda install --yes --name root pymongo
RUN ["bash", "-c", "source activate root && pip install rq-dashboard"] 
USER jovyan 


