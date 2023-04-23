FROM python:3.8-slim

RUN apt-get update && apt-get install -y netcat-traditional

WORKDIR /src

COPY requirements.txt requirements.txt
RUN pip install --no-cache-dir -r requirements.txt

COPY . .

ENTRYPOINT ["./entrypoint.sh"]
