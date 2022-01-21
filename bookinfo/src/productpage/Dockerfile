FROM python:3.7.7-slim
RUN apt-get update

COPY requirements.txt /tmp/
RUN pip install --requirement /tmp/requirements.txt

EXPOSE 9080

CMD ["python3", "productpage.py","9080"]
