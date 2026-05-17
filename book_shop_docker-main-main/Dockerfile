FROM python:3.11-slim

WORKDIR /app

ARG ARTIFACT_NAME=default.tar.gz

ADD artifacts/${ARTIFACT_NAME} /app/

RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8000

CMD ["python", "manage.py", "runserver", "0.0.0.0:8000"]
