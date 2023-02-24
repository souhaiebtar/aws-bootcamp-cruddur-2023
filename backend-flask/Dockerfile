FROM python:3.10-slim-buster

WORKDIR /backend-flask

COPY requirements.txt requirements.txt
RUN apt update && apt install -y curl && rm -rf /var/lib/apt/lists/* && \
    useradd -m app && pip3 install -r requirements.txt

COPY . .

ENV FLASK_ENV=development

USER app

EXPOSE ${PORT}
CMD [ "python3", "-m" , "flask", "run", "--host=0.0.0.0", "--port=4567"]
HEALTHCHECK --interval=30s --timeout=30s --start-period=5s --retries=3 CMD curl -f http://localhost:4567/health