FROM python:3.7
ENV PYTHONBUFFERED 1
RUN mkdir /code
WORKDIR /code
COPY requirements.txt ./code/
COPY . /code/
RUN cd /code
RUN pip install -r requirements.txt
