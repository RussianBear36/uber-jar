### Dockerfile

FROM openjdk:11

COPY . /usr/src/uberjar

CMD java -Dapp.home=/usr/src/uberjar/home -jar /usr/src/uberjar/app-core.jar