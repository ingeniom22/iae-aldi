# Dockerfile
FROM python:3.10-slim
COPY requirements.txt /userapp/requirements.txt
WORKDIR /userapp
RUN pip install -r requirements.txt
COPY . /userapp
ENTRYPOINT ["python"]
CMD ["run.py"]