FROM python:3

WORKDIR /app

COPY ./requirements.txt .
RUN pip install -r requirements.txt

COPY . .

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1
