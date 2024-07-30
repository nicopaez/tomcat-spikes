cp -avT $CATALINA_HOME/webapps.dist/manager $CATALINA_HOME/webapps/manager
https://octopus.com/blog/deployable-tomcat-docker-containers


docker run --rm -it -v$PWD:/app  azul/zulu-openjdk-alpine:8u412-jdk /bin/sh