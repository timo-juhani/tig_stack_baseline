FROM telegraf:1.18.1-alpine
LABEL author="Timo-Juhani Karjalainen, Cisco Systems"
LABEL description="TIG Stack Telegraf image"
RUN rm /etc/telegraf/telegraf.conf
COPY telegraf.conf /etc/telegraf/telegraf.conf