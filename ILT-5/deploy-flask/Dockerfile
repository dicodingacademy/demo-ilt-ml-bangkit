FROM python:3.8

COPY . /app
WORKDIR /app
RUN pip3 install -r requirements.txt

ENV FLASK_APP=main.py

CMD ["python3", "-m", "flask", "run", "--host=0.0.0.0"]
