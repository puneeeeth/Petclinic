FROM openjdk:8u151-jdk-alpine3.7

EXPOSE 8050

ENV APP_HOME /usr/src/app

COPY target/petclinic.jar $APP_HOME/petclinic.jar

WORKDIR $APP_HOME

CMD ['java','-jar','petclinic.jar']
