# 1단계: JAR 빌드된 파일만 복사해서 경량 이미지 구성
FROM eclipse-temurin:21-jdk-alpine

WORKDIR /app

# 빌드된 JAR 파일 복사 (상위 디렉터리 기준)
COPY ../../build/libs/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]