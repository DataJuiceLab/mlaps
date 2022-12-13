FROM continuumio/miniconda3
RUN apt-get update && apt-get install -y git

RUN pip3 install mlflow psycopg2-binary pymysql 
RUN conda install google-cloud-storage
# comment out boto3 if not using AWS
# comment out google-cloud-storage if not using Google


RUN cd /home && git clone https://github.com/DataJuiceLab/mlflow-example.git
