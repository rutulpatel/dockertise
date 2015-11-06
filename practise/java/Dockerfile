FROM java:latest
COPY HelloWorld.java /
#RUN apt-get update && apt-get install -y openjdk-7-jdk
RUN javac HelloWorld.java
CMD ["java", "HelloWorld"]
