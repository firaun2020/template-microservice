FROM python:3.7.3

WORKDIR /application

COPY rest_api.py /application
COPY requirements.txt /application
RUN pip install -r requirements.txt

EXPOSE 5000

CMD ["python", "rest_api.py"]