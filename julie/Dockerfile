FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Fidelcastro24/Eva-Shan /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Fidelcastro24/media

CMD ["node", "bot.js"]
