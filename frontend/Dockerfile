FROM node:16
WORKDIR /opt/app
COPY . /opt/app
RUN npm install && npm run build
EXPOSE 3001

CMD ["npm", "start"]