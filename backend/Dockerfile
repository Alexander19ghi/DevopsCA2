# Stage 1 — python:3.9 (as required by developers)
FROM python:3.9

WORKDIR /app

# Copy requirements first so install step is cached between builds
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copy application code
COPY app.py .

EXPOSE 5000

CMD ["python", "app.py"]
