FROM python:3.11-slim
WORKDIR /app
RUN pip install paradox-alarm-interface paho-mqtt
COPY run.sh /app/run.sh
RUN chmod +x /app/run.sh
CMD ["/app/run.sh"]