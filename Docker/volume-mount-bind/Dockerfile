FROM python

WORKDIR /pyapp

COPY ./new_list.py .
COPY ./user_info.txt .

CMD ["python", "new_list.py"]


#docker run -it --rm -v D:\"DevOps Learning"\DevOps\Docker\volume-mount-bind\user_info.txt:/pyapp/user_info.txt py-code