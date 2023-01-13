FROM node:14-alpine
WORKDIR /front-end
COPY ./package.json .
RUN npm install
ADD ./node_modules.tar.gz .
COPY . .
# RUN npm run build
ENTRYPOINT ["npm", "start"]
