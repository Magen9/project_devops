FROM python:3.11-slim

WORKDIR /app-flask-project

RUN pip install flask

COPY app.py .

EXPOSE 5000

CMD ["python", "app.py"]
