FROM python:3

RUN pip install --no-cache-dir -r requirements.txt

RUN mkdir -p /app
COPY ../print_version.py /app

CMD ["sh", "-c", "tail -f /dev/null"]
