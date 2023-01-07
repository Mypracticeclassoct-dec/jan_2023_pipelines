FROM ubuntu:22.04 as package
RUN  apt update && apt install git -y && apt install wget -y &&  apt install openjdk-11-jdk -y && apt install maven -y 
ADD https://jenkinspip.jfrog.io/artifactory/jenkinspip-libs-release-local/org/springframework/samples/spring-petclinic/2.7.3/spring-petclinic-2.7.3.jar  /spring-petclinic 
WORKDIR /spring-petclinic 
EXPOSE 8080
CMD [ "java","-jar","spring-petclinic-2.7.3.jar" ]