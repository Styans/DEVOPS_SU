FROM python:3.11.5-slim
WORKDIR /app
COPY requirements.txt ./
RUN pip install -r requirements.txt
COPY /app .
CMD ["python", "app.py"]