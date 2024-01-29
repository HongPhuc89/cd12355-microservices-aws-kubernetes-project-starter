FROM python:3.10.13-slim-bullseye

WORKDIR /usr/src/app

COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt
COPY . ./

CMD [ "python3", "./app.py" ]
