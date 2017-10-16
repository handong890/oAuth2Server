FROM java:8
VOLUME /tmp
VOLUME /target
ADD oauth-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8087
ENV JAVA_OPTS=""
ENTRYPOINT exec java $JAVA_OPTS -Djava.security.egd=file:/dev/./urandom -jar /app.jar