FROM eclipse-temurin:21-jdk-alpine

WORKDIR /app

# ✅ context root 기준으로 수정
COPY build/libs/*.jar app.jar

EXPOSE 8080

ENTRYPOINT ["java", "-jar", "app.jar"]
