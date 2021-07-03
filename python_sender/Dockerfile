FROM python:3.9-alpine3.14
COPY . /app
WORKDIR /app
RUN pip install requests
ENTRYPOINT ["python"]
CMD ["app.py"]


# docker build -t cevheri/python-sender-example .
# docker push cevheri/python-sender-example