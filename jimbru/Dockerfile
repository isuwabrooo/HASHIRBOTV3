FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Muhammedhashirm009/HASHIRBOTV3 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/9990hashi1/data009

CMD ["node", "bot.js"]
