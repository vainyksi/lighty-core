FROM openjdk:11-jre-slim

WORKDIR /lighty-rcgnmi
COPY LICENSE ${lighty.app.name} entrypoint.sh ./

EXPOSE 8888

ENTRYPOINT ["./entrypoint.sh", "${lighty.app.jar}"]