FROM python:3.8

COPY . /app
WORKDIR /app
RUN apt update
RUN apt install -y jq
RUN pip install -r requirements.txt
EXPOSE 8000
CMD ["python3", "-u", "/app/web.py"]
