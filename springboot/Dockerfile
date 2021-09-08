FROM    maven:3-openjdk-11-slim
RUN     mkdir -p /app/src
WORKDIR /app
COPY    src src
COPY    pom.xml .
ENV     frontend_url="http://3.234.141.206:3000"
CMD     ["mvn", "spring-boot:run"]