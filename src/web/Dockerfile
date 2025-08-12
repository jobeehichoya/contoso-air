FROM node:22
ENV PORT 3000
EXPOSE 3000

RUN mkdir -p /usr/src/app
WORKDIR /usr/src/app
##COPY src/web
COPY src/web src/web/package.json 
RUN npm install
COPY . .

CMD ["npm", "start"]
