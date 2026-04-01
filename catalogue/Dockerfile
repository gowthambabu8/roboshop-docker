FROM node:20.20.2-alphine3.23
WORKDIR /app
COPY package.json .
COPY *.js .
RUN npm install
ENV MONGO=true \
    MONGO_URL="mongodb://mongo:27017/catalogue"
CMD ["node","server.js"]



# FROM node:20
# WORKDIR /app
# COPY package.json .
# COPY *.js .
# RUN npm install
# ENV MONGO=true \
#     MONGO_URL="mongodb://mongo:27017/catalogue"
# CMD ["node","server.js"]