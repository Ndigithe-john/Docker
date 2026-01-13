FROM node

WORKDIR /app

COPY package.json /app/

RUN npm install 

COPY . /app/

ARG DEFAULT_PORT=5000

ENV PORT=$DEFAULT_PORT

# ENV MONGODB_USERNAME=root
 
# ENV MONGODB_PASSWORD=secret

EXPOSE $PORT 

CMD ["npm", "start"]