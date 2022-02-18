#what app you are creating
#what libs you are using
FROM openjdk:11

#WORKDIR specifies app Directory
WORKDIR /var/www/java

#copies the content of current directory into the WORKDIR of the docker
COPY . /var/www/java

#Execute javac command to build the application
RUN javac SampleDemo.java

#Start the application
CMD exec java SampleDemo