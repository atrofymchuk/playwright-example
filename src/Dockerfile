FROM python:3.11-slim

RUN pip3 install --no-cache-dir itsdangerous

ENV PYTHONUNBUFFERED=1

WORKDIR /srv
COPY server.py /srv/server.py

USER nobody

CMD ["python3", "/srv/server.py"]