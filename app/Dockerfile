FROM python:3

WORKDIR /app
RUN apt-get -q update -y && apt-get -q install -y gettext-base
RUN pip install flask
COPY . .
EXPOSE 5000
CMD ["/bin/bash", "start.sh"]