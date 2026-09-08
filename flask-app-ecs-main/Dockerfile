FROM python:3.14-slim

WORKDIR /app

COPY . .

RUN pip install -r requirements.txt

# expose port 80
EXPOSE 80

# serve the app / run the app (keep it running)
CMD ["python","run.py"]
  