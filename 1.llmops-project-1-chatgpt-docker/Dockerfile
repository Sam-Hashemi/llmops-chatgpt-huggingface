FROM python:3.10
COPY . .  #copy everything in my current dir to the current dir in the docker container which in this case is Python
RUN pip install -r requirements.txt
EXPOSE 80
ENTRYPOINT [ "python" ] # this is to use python as the initial command when runnig the docker run "python" .... so we dont hav eto write python anymore 
CMD [ "main.py" ]
