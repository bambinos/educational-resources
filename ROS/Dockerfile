FROM jupyter/minimal-notebook

RUN conda update -n base conda
RUN conda install -y bambi
RUN jupyter nbextension install https://github.com/drillan/jupyter-black/archive/master.zip --user
RUN jupyter nbextension enable jupyter-black-master/jupyter-black
 

