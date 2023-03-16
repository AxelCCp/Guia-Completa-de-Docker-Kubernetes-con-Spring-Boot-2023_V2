FROM openjdk:17.0.2

WORKDIR /app
	
COPY ./target/ms-cursos-server-0.0.1-SNAPSHOT.jar /app
	
EXPOSE 8002
	
ENTRYPOINT ["java","-jar","ms-cursos-server-0.0.1-SNAPSHOT.jar"]