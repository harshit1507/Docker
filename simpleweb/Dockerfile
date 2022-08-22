FROM node:alpine
RUN rm -r /app; mkdir /app
COPY ./package.json /app
WORKDIR /app
RUN npm install
COPY ./ ./
CMD ["npm", "start"]