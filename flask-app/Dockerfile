FROM python:3.7
WORKDIR /urs/scr/app
COPY . .
RUN pip install -r requirements.txt
EXPOSE 5000
ENTRYPOINT ["python"]
CMD ["./app.py"]


# this two cod below should be run
# docker build -t flask/app:v1 .
# docker run -d -p 5000:5000 --name flask-app flask/app:v1