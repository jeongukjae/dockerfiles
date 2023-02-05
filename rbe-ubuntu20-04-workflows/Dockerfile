FROM gcr.io/flame-public/rbe-ubuntu20-04-workflows:latest

RUN apt-get update \
    && apt-get install -y libatk-bridge2.0-0 \
    && rm -rf /var/lib/apt/lists/*
