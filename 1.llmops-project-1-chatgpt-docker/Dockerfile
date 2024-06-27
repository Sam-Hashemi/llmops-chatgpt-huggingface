FROM python:3.10
COPY . .  #copy everything in my current dir to the current dir in the docker container which in this case is Python
RUN pip install -r requirements.txt
EXPOSE 80
ENTRYPOINT [ "python" ]
CMD [ "main.py" ]
