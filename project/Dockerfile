FROM python:3.8

LABEL maintainer="Abdullah Meda"

WORKDIR /app

COPY ./techtrends /app

RUN pip install --no-cache-dir -r requirements.txt
RUN python3 init_db.py

EXPOSE 3111

CMD ["python3", "app.py"]