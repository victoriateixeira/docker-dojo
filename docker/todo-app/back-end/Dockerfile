FROM node:14-alpine
WORKDIR /back-end
COPY ./package.json .
RUN npm install
ADD ./node_modules.tar.gz .
COPY . .
# RUN npm run build
ENTRYPOINT ["npm", "start"]