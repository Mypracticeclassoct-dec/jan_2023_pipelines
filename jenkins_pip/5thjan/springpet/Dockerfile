FROM ubuntu:22.04 as package
RUN  apt update && apt install git -y && apt install wget -y &&  apt install openjdk-11-jdk -y && apt install maven -y 
RUN git clone https://github.com/vamsibakka/spring-petclinic.git 
WORKDIR /spring-petclinic
RUN mvn clean package
EXPOSE 8080
CMD [ "java","-jar","/target/spring-petclinic-2.7.3.jar" ]