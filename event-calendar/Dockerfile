FROM python:3.8.4
ENV PYTHONUNBUFFERED=1
WORKDIR /usr/src/app
COPY ./  /usr/src/app
COPY requirements.txt ./
RUN pip3 install -r requirements.txt
RUN apt-get -y update
RUN pip install --upgrade pip