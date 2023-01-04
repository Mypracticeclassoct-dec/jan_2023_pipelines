FROM ubuntu:22.04
RUN apt update && api install openjdk-11-jdk -y \
     && apt install nodejs -y \
     && apt install npm -y \
     && git clone https://github.com/Mypracticeclassoct-dec/js-e2e-express-server_jan2023.git 
WORKDIR /js-e2e-express-server_jan2023
RUN npm install
CMD [ "npm", "start" ]
