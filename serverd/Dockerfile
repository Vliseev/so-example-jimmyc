FROM python:3.6

RUN mkdir src
ADD serverd.py /src/
RUN pip install pyzmq
WORKDIR /src/
EXPOSE 5557
