FROM python:3.11-slim

WORKDIR /usr/src/app

COPY . .

RUN apt update -y && \
    pip install --no-cache-dir -r requirements.txt

COPY . .

EXPOSE 5153

CMD [ "python", "./app.py" ]
