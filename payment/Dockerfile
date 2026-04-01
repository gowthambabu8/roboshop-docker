FROM python:3.9
EXPOSE 8080
WORKDIR /app
COPY payment.ini .
COPY requirements.txt .
COPY *.py .
RUN pip3 install -r requirements.txt
CMD ["uwsgi","--init","payment.ini"]