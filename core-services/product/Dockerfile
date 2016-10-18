# FROM anapsix/alpine-java:jre8
FROM java:8
WORKDIR /data

CMD ["bash"]

ADD target/core-product-0.1-SNAPSHOT.jar /data/core-product.jar

CMD java -jar -Dspring.profiles.active=docker core-product.jar
