FROM node:alpine 

WORKDIR /frontend

# Installing dependencies
COPY ./package.json /frontend
RUN npm install

# Copying all the files in our project
COPY . .

# Starting our application
CMD npm start
