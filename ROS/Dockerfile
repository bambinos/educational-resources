FROM jupyter/minimal-notebook

RUN conda update -n base conda

# Install from pip because conda is outdated right now
RUN pip install bambi

RUN jupyter nbextension install https://github.com/drillan/jupyter-black/archive/master.zip --user
RUN jupyter nbextension enable jupyter-black-master/jupyter-black
 

