#specify parent image
FROM node:17-alpine
#working directory of the image
WORKDIR /app 
# copy all source files
COPY . .
#run npm install to add all dependencies
RUN npm installex
#port
EXPOSE 4000 
#command will run when container based on image is run 
CMD [ "node", "app.js" ]
#docker build -t myapp .