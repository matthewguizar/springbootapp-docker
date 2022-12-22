Using dockerfile to enable use of java spring boot application
cloned sample project and created jar file of it to run

1.add into folder
2. use cmd to go into folder
3. use command docker build -t spring-boot-docker . (tags the image as spring-boot-docker)
4. once done/completed use command docker run -d -p 8080:8080 spring-boot-docker


docker build -t spring-boot-docker .

