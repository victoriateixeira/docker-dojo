FROM mjgargani/puppeteer:trybe1.0
WORKDIR /tests
COPY ./package.json .
RUN npm install
ADD ./node_modules.tar.gz .
COPY . .
# RUN npm run build
ENTRYPOINT ["npm", "test"]
