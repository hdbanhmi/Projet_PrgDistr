# Étape 1 : Utiliser une image Java officielle comme base
FROM openjdk:17-jdk-slim

# Étape 2 : Définir le répertoire de travail
WORKDIR /app

# Étape 3 : Copier le fichier JAR généré
COPY target/task-service-0.0.1-SNAPSHOT.jar app.jar

# Étape 4 : Exposer le port sur lequel l'application s'exécute
EXPOSE 8080

# Étape 5 : Lancer l'application
ENTRYPOINT ["java", "-jar", "app.jar"]