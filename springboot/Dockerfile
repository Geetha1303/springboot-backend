FROM    maven:3-openjdk-11-slim
RUN     mkdir -p /app/src
WORKDIR /app
COPY    src src
COPY    pom.xml .
ENV     frontend_url="http://34.200.242.6:3000"
CMD     ["mvn", "spring-boot:run"]