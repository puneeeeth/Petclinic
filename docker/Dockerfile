FROM openjdk:8u151-jdk-alpine3.7

ENV APP_HOME /usr/src/app

COPY target/petclinic.jar $APP_HOME/petclinic.jar

WORKDIR $APP_HOME

EXPOSE 9000

CMD ['java','-jar','petclinic.jar']
