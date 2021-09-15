FROM quay.io/lyfe00011/test:beta

RUN git clone https://github.com/kannan/comrade-bot/root/CoMrAdE/Duplicated
WORKDIR /root/CoMrAdE/Duplicated/
RUN yarn install --no-audit
RUN git clone https://github.com/kannan/comrade-bot/media
RUN cp -R /root/Utils/* /root/CoMrAdE/Duplicated 
CMD ["node", "bot.js"]
