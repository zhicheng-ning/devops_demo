FROM ahawker/jre8

MAINTAINER ningzhicheng

VOLUME /tmp

ADD ./target/*.jar /login.jar

ENTRYPOINT ["java","-jar","/login.jar"]

EXPOSE 8000