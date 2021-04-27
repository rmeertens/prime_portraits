FROM python:3.8 

RUN apt-get install -y unzip
RUN apt-get install -y git

RUN pip3 install jupyter
RUN pip3 install matplotlib
RUN pip3 install Pillow==4.1.1
RUN pip3 install image
RUN pip3 install scikit-image
RUN pip3 install scikit-learn

COPY jupyter_notebook_config.py /root/.jupyter/
COPY run_jupyter.sh /
RUN chmod +x /run_jupyter.sh

WORKDIR "/notebooks" 
CMD ["/run_jupyter.sh"]

