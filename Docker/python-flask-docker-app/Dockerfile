FROM python:3.6
MAINTAINER Thufel "shaikthufel108@gmail.com"
COPY . /usr/app
WORKDIR /usr/app
EXPOSE 5000
RUN pip install -r requirements.txt
ENTRYPOINT ["python", "app.py"]
