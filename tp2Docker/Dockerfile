FROM python:2.7-alpine
WORKDIR /app
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt 
EXPOSE 5000:5000
ENTRYPOINT ["python","app.py"]
