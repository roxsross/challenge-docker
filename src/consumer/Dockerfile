FROM python:3.10.8-alpine
WORKDIR /app
COPY requirements.txt /app
RUN pip install -r requirements.txt
COPY . /app
CMD [ "python","consumer.py" ]

