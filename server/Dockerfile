FROM python:3

WORKDIR /app

ENV FLASK_APP=app.py

ENV FLASK_ENV=developemnt

COPY ./requirements.txt .

RUN pip install -r requirements.txt

COPY . .

ENTRYPOINT [ "python" ]

CMD ["app.py"]