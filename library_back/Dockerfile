FROM python:3

WORKDIR /app/library_back

COPY ./requirements.txt .
RUN pip install -r requirements.txt

COPY . .

ENV PYTHONDONTWRITEBYTECODE=1
ENV PYTHONUNBUFFERED=1

EXPOSE 8000
