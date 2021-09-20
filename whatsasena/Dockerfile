FROM fusuf/whatsasena:latest

RUN git clone ellem copy https://github.com/Daxo-ser/Sophia /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit

CMD ["node", "bot.js"]
