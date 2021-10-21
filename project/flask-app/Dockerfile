FROM python:2.7
COPY . /flask-app
WORKDIR /flask-app
RUN apt update --yes
RUN apt install nodejs npm --yes
RUN pip install -r requirements.txt 
ENTRYPOINT [ "python" , "app.py"]