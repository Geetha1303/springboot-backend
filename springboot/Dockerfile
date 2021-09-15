FROM    maven:3-openjdk-11-slim
RUN     mkdir -p /app/src
WORKDIR /app
COPY    src src
COPY    pom.xml .
ENV     frontend_url="react.gvdevops.online"
ENV     MONGO_URL="mongo.gvdevops.online"
CMD     ["mvn", "spring-boot:run"]