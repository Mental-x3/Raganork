FROM fusuf/whatsasena:latest
RUN git clone https://github.com/Mental-x3/Raganork /Mental/Raganork
WORKDIR /Mental/Raganork
ENV TZ=Asia/Kolkata
RUN npm install supervisor -g
RUN yarn install --ignore-engines
CMD ["node", "index.js"]
