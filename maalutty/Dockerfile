FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Ammuponnu2/subinsree /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Europe/Istanbul
RUN npm install supervisor -g
RUN yarn install --no-audit
RUN git clone https://github.com/Ammuponnu2/media

CMD ["node", "bot.js"]
