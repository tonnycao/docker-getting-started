FROM python:3.6-alpine
ADD . /code
WORKDIR code
RUN pip install redis flask
CMD ["python3", "app.py"]