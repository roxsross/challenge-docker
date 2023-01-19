FROM python:3.10.8-alpine
WORKDIR /app
COPY . /app
RUN pip install -r requirements.txt
CMD ["python","consumer.py"]