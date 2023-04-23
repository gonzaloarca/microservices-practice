FROM python:3.11

COPY . .

RUN pip install -r requirements.txt

CMD ["nameko", "run", "--config", "config.yml", "airports"]
