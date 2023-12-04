FROM python:alpine

EXPOSE 8080

USER robo

WORKDIR /app

COPY . /app/

RUN pip install -r requirements.txt

ENV AMQP_USER=roboshop \
    AMQP_PASS=roboshop123

CMD ["uwsgi", "--ini", "payment.ini"]