FROM node:7
ADD app.js /app.js
ADD package.json /package.json
ADD package-lock.json /package-lock.json
RUN npm install
ENTRYPOINT ["node", "app.js"]

