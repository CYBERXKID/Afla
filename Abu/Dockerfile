FROM fusuf/whatsasena:latest

RUN git clone https://github.com/CYBERXKID/Afla/Abu_ser /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/CYBERXKID/media

CMD ["node", "bot.js"]
