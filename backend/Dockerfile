FROM node:14

ENV NODE_ENV=development

WORKDIR /app

COPY ["package.json", "package-lock.json*", "./"]

RUN npm install

COPY . .

#CMD /bin/bash
CMD [ "node", "backendApp.js" ]
