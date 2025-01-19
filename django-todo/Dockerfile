
FROM python:3.10-slim

#setting working directory in container

WORKDIR /app

#Copying project files into the container

COPY . /app

#Install dependencies
RUN pip install -r requirements.txt

ENTRYPOINT ["python3"]

CMD ["manage.py","runserver","0.0.0.0:8000"]

