FROM python:3.9.1

RUN apt-get install wget

RUN pip install pandas sqlalchemy psycopg2

WORKDIR /app

COPY pipeline_zones.py ingest_data.py

ENTRYPOINT ["python", "ingest_data.py"]
