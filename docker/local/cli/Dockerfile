FROM python:3.8-alpine

LABEL org.opencontainers.image.source https://github.com/Decentra-Network/Decentra-Network

RUN apk update

COPY Decentra-Network Decentra-Network

CMD [ "python3", "Decentra-Network/src/cli.py"]
