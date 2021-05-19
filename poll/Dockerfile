FROM python:slim-buster
WORKDIR .
ENV FLASK_APP app.py
ENV FLASK_RUN_HOST 0.0.0.0
COPY . ./
RUN pip3 install -r requirements.txt
EXPOSE 80
CMD ["flask", "run", "--host=0.0.0.0", "--port=80"]