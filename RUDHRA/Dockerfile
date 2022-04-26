FROM fusuf/whatsasena:latest

RUN git clone https://github.com/Neymar-boy/Niyamwol-v2 /root/WhatsAsenaDuplicated
WORKDIR /root/WhatsAsenaDuplicated/
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
RUN git clone https://github.com/Neymar-boy/files

CMD ["node", "bot.js"]
