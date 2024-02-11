FROM python:3.12
RUN apt-get update
RUN pip3 install streamlit requests
COPY ./main.py /main.py
COPY ./test.py /test.py
COPY ./requirements.txt /requirements.txt
EXPOSE 3000
