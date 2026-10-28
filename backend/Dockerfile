FROM python:3.12.8-slim-bookworm

WORKDIR /app

RUN groupadd --system app && useradd --system --gid app --create-home --home-dir /home/app app

COPY requirements.txt ./requirements.txt
RUN pip install --no-cache-dir --upgrade pip && \
    pip install --no-cache-dir -r requirements.txt

COPY app.py ./app.py

RUN chown -R app:app /app
USER app

CMD ["python", "app.py"]
