# Dockerfile
FROM python:3.10-slim
COPY requirements.txt /orderapp/requirements.txt
WORKDIR /orderapp
RUN pip install -r requirements.txt
COPY . /orderapp
ENTRYPOINT ["python"]
CMD ["run.py"]