#  Video https://youtu.be/a0Dm2Wiy2E0

Dockerfile
```Dockerfile
FROM debina
LABEL

RUN apt-get update
VOLUME /diretory
ADD file.txt /diretory/
COPY file2.txt /diretory
ENTRYPOINT ["usr/bin/..."]
CMD ["sh","-c","echo","$home"]
ENV name="value"
USER catalunha
WORKDIR /folder
```
