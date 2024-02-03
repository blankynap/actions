FROM nginx
RUN apt update && apt clean
RUN apt install tmux git iputils-ping
EXPOSE 8080
CMD ["nginx", "-g", "daemon off;"]
