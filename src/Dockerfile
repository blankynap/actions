FROM python:3.12
RUN apt update && apt clean
RUN apt install tmux git iputils-ping -y
RUN pip3 install streamlit
COPY ./main.py /main.py
EXPOSE 5000
