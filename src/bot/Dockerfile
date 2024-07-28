FROM python:3.12

WORKDIR /app

COPY . .

RUN apt-get update && apt-get install -y gcc g++ ffmpeg

RUN pip install -r requirements.txt