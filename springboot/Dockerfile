FROM    maven:3-openjdk-11-slim
RUN     mkdir -p /app/src
WORKDIR /app
COPY    src src
COPY    pom.xml .
CMD     ["mvn", "spring-boot:run"]