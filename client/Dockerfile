FROM node:19-alpine
RUN mkdir /frontend
WORKDIR /frontend
COPY package.json /frontend
EXPOSE 3000
RUN npm install
CMD ["npm", "run", "dev"]