FROM python:3.7.7-slim
RUN apt-get update

RUN python3 -m pip install -r requirements.txt

EXPOSE 9080

CMD ["python3", "productpage.py","9080"]
