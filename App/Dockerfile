FROM python:3.11.2-slim-buster

ADD . ./test

WORKDIR /test

RUN pip install -r requirements.txt

EXPOSE 5003

CMD ["streamlit","run","App.py"]