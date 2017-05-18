FROM node:7-alpine

RUN npm install -g gulp

ADD loop.sh /usr/bin/loop.sh
RUN chmod +x /usr/bin/loop.sh
CMD ["/usr/bin/loop.sh"]