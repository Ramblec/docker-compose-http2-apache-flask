FROM python:3.8

RUN mkdir /usr/src/app 
WORKDIR /usr/src/app 
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

CMD ["uwsgi","--ini","uwsgi.ini"]
