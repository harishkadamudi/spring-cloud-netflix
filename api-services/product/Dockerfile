# FROM anapsix/alpine-java:jre8
FROM java:8
WORKDIR /data

CMD ["bash"]

ADD target/api-product-0.1-SNAPSHOT.jar /data/api-product.jar

CMD java -jar -Dspring.profiles.active=docker api-product.jar

EXPOSE 8080
