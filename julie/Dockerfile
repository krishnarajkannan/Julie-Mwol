FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/kannan/comrade-bot/root/pis__ton/Duplicated
WORKDIR /root/pis__tonDuplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/kannan/comrade-bot/media
RUN cp -R /root/Utils/* /root/pis__tonDuplicated 
CMD ["node", "bot.js"]
