# syntax=docker/dockerfile:1
FROM python:3
ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
WORKDIR /library_back
COPY requirements.txt /library_back/

RUN pip install -r requirements.txt

COPY . /library_back/
