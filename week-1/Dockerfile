# what kind of base image
FROM python:3.9

RUN pip install pandas

WORKDIR /app

# host to destination

COPY pipeline.py pipeline.py

ENTRYPOINT ["python","pipeline.py"]

