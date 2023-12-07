#pull base java
#
FROM openjdk:11

#create a working directory to copy all the files
WORKDIR /app


# Code copy to image for running continer 
COPY Hello.java /app

#Compile the code
RUN javac Hello.java

# App is now ready to run , pass the arguments
CMD ["java","Hello"]
